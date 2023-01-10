# TagMyWatch ⌚

Data Science project for the recognition and pricing of watch models in the second-hand market.

The project is based on a classification model through a Neural Network for the detection of the watch model through an image and a regression model for the prediction of its price in the second-hand market, through features such as the price, condition or material of the watch.

![Captura de pantalla_20230110_115442](https://user-images.githubusercontent.com/119113483/211534190-2bd29697-5ca8-4eae-8524-3557573e5104.png)


## Technologies 💻

* Programming language: Python
* Main libraries: Numpy, Pandas, Scikit-Learn
* Data visualization: Matplotlib, Seaborn
* WebScrapping: Requests, BeautifulSoup
* Neural Networks | Deep Learning: TensorFlow, Keras
* Regression Models: LinearRegression, LightGBM, CatBoost, XGBoost
* Organization: Notion + Miro

## Objectives 📋

* The development of a neural network which is capable of detecting the model of a clock from a photo or image provided by the user.

* Implementation of a predictive model that, based on certainwatch features provided by the user, be adaptedto throw as accurately as possible the price of that watch in the second hand market

## Data 🗂️

* The data source is extracted from the Chrono24.com website (Reference in buying and selling of second-hand watches)
* Compilation of 1,500 images of the models selected for classification: Rolex Submariner Date, Cartier Santos 100, Omega Speedmaster Moonwatch, Patek Philippe Nautilus and Hublot Big Bang
* Compilation of 15,000 data records of the brands selected for valuation: Rolex, Cartier, Omega, Patek Philippe, Hublot, Seiko, Tissot, Hamilton, Richard Mille and Casio.

## EDA 📊📈

We can see a preview of some elements of the exploratory analysis

![Captura de pantalla_20230110_122014](https://user-images.githubusercontent.com/119113483/211538142-a55ad876-ed3f-40f7-ad3d-eed362a0f39b.png)


![Captura de pantalla_20230110_122025](https://user-images.githubusercontent.com/119113483/211538063-e183502c-9fce-45bc-837a-beee6e175d28.png)


![Captura de pantalla_20230110_122041](https://user-images.githubusercontent.com/119113483/211538226-4aac04fd-15d9-4bcd-834e-d734577d6d1f.png)


## MODELS ⚙️👨🏻‍💻

### Neural Network
* Creation of neural network from scratch with Keras engine
* Black and white images for model enhancement
* Search for pre-trained neural networks for improve accuracy.
* Choice of VGG16 Neural Network with various layers Dense and Dropout to avoid overfit

![Captura de pantalla_20230110_122653](https://user-images.githubusercontent.com/119113483/211540137-e0a9b644-3d07-4753-b26d-214fdc558bbb.png)

![Captura de pantalla_20230110_122728](https://user-images.githubusercontent.com/119113483/211540320-0cf11c56-8239-4635-a59b-8ada3f274acc.png)

### Linear Regression 

* Various regression and gradient boosting models were applied.
* GridSearch was applied to search for hyperparameters: Depth, Learning Rate, n_iterations.
* Train and test metrics were compared to assess possible overfit

![Captura de pantalla_20230110_123052](https://user-images.githubusercontent.com/119113483/211540932-c205a059-e66b-40b6-bf4c-f78d8dbaa6d9.png)


## Deployment 📲

* We create an interface with both models (Neural Network and Regression)
* We unfold the model using the Gradio python library

![Captura de pantalla_20230110_123309](https://user-images.githubusercontent.com/119113483/211541357-4570e0c5-b483-4e14-bdbb-ba8998a65ced.png)
![Captura de pantalla_20230110_123300](https://user-images.githubusercontent.com/119113483/211541364-967d2ab8-a1f2-4c32-9736-7a28b8c08059.png)


## Conclusions 🙇🏻

* It is possible to create a neural network that distinguishes between watches and a predictive price model.
* Iterative process: Using models as an exploratory technique.

## Future Improvements 💭

* Improve interface design and deploy the model on the network.
* Expand models and brands in Neural Network and Models of Regression.
* Cluster creation.
* Create a prediction with confidence intervals in the regression model.



<h1 align = "center">ML models</h1> <hr>
 <p>Some ML models created just for fun</p>
    <ol>
        <li><h2>Sports Image Classification - </h2>
            <p>  The project aims to develop a Convolutional Neural Network (CNN) model for image classification using TensorFlow and Keras. The project involves data preprocessing, model building, training, and                     evaluation. The dataset is available on <a href = "https://www.kaggle.com/datasets/sidharkal/sports-image-classification">kaggle.com</a>. The model classifies the images into 7 class( different                      types of sports) - <br>
            <ul>
                <li>Badminton</li>
                <li>Cricket</li>
                <li>Karate</li>
                <li>Soccer</li>
                <li>Swimming</li>
                <li>Tennis</li>
                <li>Wrestling</li>
            </ul> <p>
            <h3>Libraries used:-</h3>
            <ul>
                <li><b>TensorFlow & Keras</b>: For building and training the CNN model.</li>
                <li><b>ImageDataGenerator</b>: For real-time data augmentation and loading images in batches during training.</li>
                <li><b>NumPy</b>: For numerical operations.</li>
                <li><b>Pandas</b>: For data manipulation and handling CSV files.</li>
                <li><b>Matplotlib</b>: For generating graph.</li>
                <li><b>Callbacks</b>: For termination of epoch on reaching 99% train accuracy.</li>
            </ul></p>
           <p>
              <h3>Data:</h3>
              <ul>
                  <li><b>Training and Testing Data</b>: Loaded from CSV files (train.csv and test.csv).</li>
                  <li><b>Image Dimensions</b>: Images are resized to (150, 150) pixels.</li>
                  <li><b>Batch Size</b>: Set to 32.</li>
                  <li><b>Data Augmentation</b>:
                       <ul>
                          <li><b>Training data and Testing data</b>: Normalization of pixel values to [0,1].
                       </ul>
                  </li>
              </ul>
           </p>
           <p>
               <h3>Model Architecture and Compilation:</h3>
               <ul>
                   <li><b>Input Shape</b>: (224, 224, 3) - RGB images.</li>
                   <li><b>Layers</b>:
                    <ul>
                        <li>Conv2D with ReLU activation. </li>
                        <li>MaxPooling2D for downsampling.</li>
                        <li>Flatten layer to flatten the 2D array to a 1D array.</li>
                        <li>Dense layers with ReLU activation.</li>
                        <li>Final Dense layer with softmax activation for multi-class classification (7 classes).</li>
                    </ul>
                   </li>
                   <li> <b> Optimizers</b>: Adam Optimizer</li>
                   <li> <b>Loss Function</b>: Categorical Crossentropy</li>
                   <li> <b>Metrics</b>: Accuracy</li>
               </ul>
          </p>
          <p>
             <h3>Summary:</h3>
                 This project follows a standard workflow for image classification:
             <ol>
                <li>Data loading and preprocessing.</li>
                <li>Building a CNN model.</li>
                <li>Compiling the model with appropriate optimizer and loss.</li>
                <li>Training the model with augmented data.</li>
                <li>Evaluating the model's performance using validation data.</li>
             </ol>
          </p>
   
</ol>

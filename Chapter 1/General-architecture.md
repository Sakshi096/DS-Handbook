# Various Steps Involved

- **Business Understanding** - Understanding the given use case, good to know more about the domain for which the use cases are built.

- **Data Acquisition and Understanding** - Gathering data from different resources and understanding the data. Cleaning data, performing EDA, etc.

- **Modeling** - Building a model using the acquired data. Feature engineering, feature selection.

- **Evaluation** - Evaluating the performance of the given model on unseen data.

- **Prediction** - Using the trained model to predict values for new observations.

  Post prediction, if the accuracy is not high, we tune the model either by changing the algorithm, feature selection, or by just gathering more data.

- **Deployment** - After building a good model and tuning it as required, we can deploy this model in production to predict values for new observations, either in the cloud or on a Raspberry Pi. Monitor the model performance after deployment. If it's good, go live or re-iterate the above process until the performance is up to the mark.

Even after all of this, if the model again performs poorly on new/unseen data, we repeat all the above processes all over again.

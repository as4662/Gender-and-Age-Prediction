# Gender-and-Age-Prediction

Automatic prediction of age and gender from face images has drawn a lot of
attention recently,due it is wide applications in various facial analysis problems.
However, due to the large intra-class variation of face images (such as variation
in lighting, pose, scale, occlusion), the existingmodels are still behind the desired
accuracy level, which is necessary for the use of thesemodels in real-world
applications. In this work, we propose a deep learning framework, basedon the
ensemble of attentional and residual convolutional networks, to predict gender
and agegroup of facial images with high accuracy rate. Using attention
mechanism enables our model tofocus on the important and informative parts of
the face, which can help it to make a moreaccurate prediction. We train our model
in a multi-task learning fashion, and augment thefeature embedding of the age
classifier, with the predicted gender, and show that doing so canfurther increase
the accuracy of age prediction. Our model is trained on a popular face age
andgender dataset, and achieved promising results. Through visualization of the
attention maps ofthe train model, we show that our model has learned to become
sensitive to the right regions ofthe face.

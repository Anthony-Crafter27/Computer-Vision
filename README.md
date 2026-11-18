<!--I already know a little bit of HTML, so I did this by hand for fun.-->
<h1>Computer Vision</h1>
<h2>Project Description</h2>
<p>This project uses Google's Teachable Machine in order to classify objects found on my desk.</p>
<h2>Classes Identified</h2>
<ul>
  <li>Class 1: Mouse</li>
  <li>Class 2: Phone</li>
  <li>Class 3: Wallet</li>
  <li>Class 4: Water Bottle</li>
</ul>
<h2>Discussion & Reflection</h2>
<ol>
  <li>
    <h3>Model Performance & Iteration:</h3>
  </li>
    <ul>
      <li>How accurate was your first trained model?</li>
      <p>- I would say that my first trained model wasn't the most accurate.</p>
      <li>What steps did you take to iterate and improve its performance?</li>
      <p>- I took more pictures of each item at different angles in order to try and improve its performance.</p>
      <li>How did these changes affect the model's accuracy and confidence scores?</li>
      <p>- I think these changes helped in making the model more accurate.</p>
    </ul>
  <li>
    <h3>Challenges & Observations:</h3>
  </li>
    <ul>
      <li>Which objects were the easiest for your model to learn and distinguish? Why do you think that was?</li>
      <p>- The water bottle was the easiest for my model to learn and distinguish. I think this is the case, since the images taken of it might've been easier for the AI to comprehend.</p>
      <li>Which objects were the most challenging? What made them difficult?</li>
      <p>- I would say the mouse and phone were the most challenging. I think the thing that made them more difficult for the AI to figure out was the lack of quality of the images, since I was still trying to figure out how I should angle my webcam in order to get image data for the AI.</p>
      <li>What happened when you Showed the model an object it wasn't trained on? How did the confidence scores behave, and why is this significant?</li>
      <p>- When the model saw my face, it said I was a water bottle. Last time I checked, I didn't look like a water bottle. The confidence scores showed 100% in the water bottle category, with 0% on everything else. I think this is significant, since this could be a sign of overfitting.</p>
    </ul>
  <li>
    <h3>Bias in AI:</h3>
  </li>
    <ul>
      <li>If you only trained your "mug" class with images of *your specific mug* how well do you think it would recognize other students' significantly different mugs? how does this illustrate the concept of bias being introduced through training data?</li>
      <p>- If I only trained my water bottle class with images of my water bottle, I don't think it would be able to recognize other students' significantly different water bottles all too well. I think there is a chance it might be able to see the plastic bottle shape of a water bottle of a different brand and classify it correctly, but it could very well be a 50/50 chance. I think this illustrates the concept of bias by showing me that the AI will most likely either default to whatever it knows best, or it will see an image of my face with similar noise to the image of the water bottle and default to guessing that I'm a water bottle.</p>
      <li>Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?</li>
      <p>- If I tried to use the model in a dimly lit room with strong shadows after training it off of images taken in bright, direct lighting, I think it would most likely misclassify whatever is placed in front of it. I think a biased AI wouldn't be very robust when it comes to looking at new data, since it would have memorized whatever it was given instead of learning the outlines and general makeup of each item, causing bias in the first place.</p>
    </ul>
  <li>
    <h3>Model Limitations & Usefulness:</h3>
  </li>
    <ul>
      <li>What are some key limitations of the model you created?</li>
      <p>- I think the fact that I didn't have access to different styles of each item was a pretty big limitation, since if I were to show the model a white wallet instead of my black wallet, it would most likely mistake it as something else. I also think that not having the time to take hundreds of thousands of images of each item in order to properly train the model was another limitation.</p>
      <li>Why is it useful to be able to download your trained model files and share them? What does this enable?</li>
      <p>- I think it is useful to be able to download my trained model files and share them, so that other people can see them, use them, and be able to make suggestions in order to make the model better. This seems to enable the ability to bug fix and version the model in order to make a better model, similar to what they do with ChatGPT and other AI models.</p>
    </ul>
  <li>
    <h3>Real-World Application & Ethics:</h3>
  </li>
    <ul>
      <li>Brainstorm 2-3 real-world applications where a similar image classification model could be useful.</li>
      <p>- I think a similar image classification model could potentially be used to monitor manufactured items for physical defects, looking at x-ray images for broken bones, or to check for spoiled food in a refrigerator.</p>
      <li>Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world.</li>
      <p>- I think developers should keep in mind to not feed image recognition AI images of sensitive and private information, since this could be seen as highly unethical and illegal, especially if done without consent. There should also be a way to opt out of sharing video and images of yourself for the purpose of training an AI, since people might want to retract consent if they don't feel comfortable.</p>
    </ul>
</ol>

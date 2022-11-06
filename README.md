#Inspiration
Climate change has affected billions of people around the world and remains an existential threat to humanity. Technological breakthroughs have allowed us to become much more aware of our climate footprint and help us move towards a sustainable future for all. We believe that the next step for sustainability is to utilize innovative machine learning models to bring the fight against climate change into the hands of the people.

#What it does
enviroptimize is an application that is designed around making the end user more aware of their climate footprint. One of the most effective ways that individuals can become climate-conscious is to become more conscious of the environmental impact of the foods they consume, and reduce the amount of thrown out food, or waste. The application aims to utilize an intelligent ML model in order to address this.

1) In a predetermined database, a sustainability score is generated based on three equally weighted factors: a) manufacturing carbon footprint, b) transportation carbon footprint, and c) overall carbon footprint of the product category. 2) The user takes a picture of their groceries, or their refrigerator. 3) The application analyzes the food in the picture using a 10,000 image machine learning model and matches the food up to its sustainability score. 4) A list of the user's food is generated, along with each food's sustainability score. 5) Items that are duplicates are also highlighted to the user. 6) Recommendations to reduce waste are provided to the user. 7) Interesting recipes from the current food that the user has are generated based on the matches.

#How we built it
We used Figma to create a frontend demonstration as to how the app would actually be deployed as a finished product. We utilized CoreML to build a machine learning model that helps the application identify different types of foods. The machine learning model was trained using a minimized version of the TensorFlow Food101 dataset, which contains over 100,000 images of food. We utilized Xcode and Swift and a demo application from Apple Developer in order to deploy an application onto iOS/iPadOS and test out the machine learning model.

#Challenges we ran into
Conceptualizing the different interactions between parts of the application was definitely a challenge. The goal was to theorize a way to make the experience as seamless as possible to the end user. We utilized a physical development model in order to overcome these challenges and create a successful demo application.

#Accomplishments that we're proud of
We're definitely proud of being able to successfully utilize CoreML, as none of us really had that much experience with that realm of software development prior to this hackathon.

#What we learned
We definitely learned a lot about how to utilize newer technologies such as machine learning and vision systems to combat challenges that have been ongoing, such as climate change. We hope that this will inspire more people in the future to develop innovative solutions to address global issues.

#What's next for enviroptimize
The next step for enviroptimize is to add more data to the machine learning model in order to perfect the image recognition for most generic items. We also plan to talk to real climate experts on how to utilize these technologies and integrate them in innovative ways.

#Built With
coreml
figma
swift
tensor-flow
xcode

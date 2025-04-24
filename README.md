# XRticulate
3DUI &amp; AR Final Project - Selecting, Filtering, Manipulating, and Navigating with LLMs in XR

# Project Setup

1. Take the following scripts in the Library PackageCache/voice2action@ae562397a9 folder and replace the respective scripts in Packages/Voice2Action/Runtime:

- VoiceIntentController
https://github.com/michellesynlee/XRticulate/blob/main/Library/PackageCache/voice2action%40ae562397a9/Runtime/VoiceIntentController.cs


- ShapeController

- PropertyExtractor

- PropertyExecutor



2. Set up OpenAPI key and Organization Id:

Go to Assets -> Resources -> OpenAIConfiguration then paste in the values



3. Scenes

Main scene: Packages/Voice2Action/Samples/Starter Assets/Starter Scene Complete


# Debugging

1. Rendering Issues

If the materials look pink, you must convert the shader:

Edit -> Rendering -> Materials -> Convert

Then drag the material onto each element of the scene

2. Cannot open scene in read-only

Go to package manager -> voice2action -> samples and reimport the folder
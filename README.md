# PhotoSharing
Screenshot - Save on Native Device - Share on Social Networks
---
### Android and IOS
---
That's perfect for AR experience

## Main Scene
UIManager manages the screen capture behavior with the ui.
I inserted two canvases because one is flexible while the other is pixel perfect and they have different purposes.
The first manages the default screen while the second the preview of the screenshot
<img width="1222" alt="Schermata 2020-06-11 alle 00 06 06" src="https://user-images.githubusercontent.com/9513748/84323782-b5562100-ab77-11ea-8e44-2e7dcb7f47e2.png">

## Some Actions
- Bind the PreviewContainer's button to LaunchPreview method
<img width="360" alt="Schermata 2020-06-11 alle 00 06 35" src="https://user-images.githubusercontent.com/9513748/84324853-b5efb700-ab79-11ea-808c-4b9a97be8ffc.png">

- Bind the CameraButton's button to TakeScreenshot method.
<img width="353" alt="Schermata 2020-06-11 alle 00 06 42" src="https://user-images.githubusercontent.com/9513748/84325826-f2bcad80-ab7b-11ea-8e5a-fcb82c5fe9bb.png">

- In UIPane script from PreviewImage game object type PreviewImage for Identity field and flag Interactable.
<img width="432" alt="Schermata 2020-06-11 alle 00 07 06" src="https://user-images.githubusercontent.com/9513748/84325838-f8b28e80-ab7b-11ea-9c82-d2b749242f33.png">

- Bind the CloseButton's button to showCanvases method.
<img width="427" alt="Schermata 2020-06-11 alle 00 07 14" src="https://user-images.githubusercontent.com/9513748/84325844-fb14e880-ab7b-11ea-964b-c3c8ca00be31.png">

- Bind the ShareButton's button to SharePreview method.
<img width="429" alt="Schermata 2020-06-11 alle 00 07 23" src="https://user-images.githubusercontent.com/9513748/84325847-fc461580-ab7b-11ea-92d7-8649fd410ee7.png">


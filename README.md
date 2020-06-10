# PhotoSharing
Screenshot - Save - Share

## Main Scene
UIManager manages the screen capture behavior with the ui.
I inserted two canvases because one is flexible while the other is pixel perfect and they have different purposes.
The first manages the default screen while the second the preview of the screenshot
<img width="1222" alt="Schermata 2020-06-11 alle 00 06 06" src="https://user-images.githubusercontent.com/9513748/84323782-b5562100-ab77-11ea-8e44-2e7dcb7f47e2.png">

## Some Actions
- Bind the PreviewContainer's button to LaunchPreview method
<img width="360" alt="Schermata 2020-06-11 alle 00 06 35" src="https://user-images.githubusercontent.com/9513748/84324853-b5efb700-ab79-11ea-808c-4b9a97be8ffc.png">

- Bind the CameraButton's button to TakeScreenshot method.

- In UIPane script from PreviewImage game object type PreviewImage for Identity field and flag Interactable.

- Bind the CloseButton's button to showCanvases method.

- Bind the ShareButton's button to SharePreview method.


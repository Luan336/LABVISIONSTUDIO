# LABVISIONSTUDIO
Projeto criado para o vision study
Projeto criado para o vision study Detectar rostos no Vision Studio As ferramentas para detectar rosto, ler texto e analizar imagens segue o processo inicial abaixo que é comum para todos os recursos.
A common computer vision challenge is to detect and interpret text embedded within an image. This is known as optical character recognition (OCR). In this exercise you’ll use an Azure AI services resource, which includes Azure AI Vision services. You’ll then use Vision Studio to try out OCR with different types of images.

Create an Azure AI services resource
You can use Azure AI Vision’s OCR capabilities with an Azure AI services multi-service resource. If you haven’t already done so, create an Azure AI services resource in your Azure subscription.

In another browser tab, open the Azure portal at https://portal.azure.com, signing in with the Microsoft account associated with your Azure subscription.

Click the ＋Create a resource button and search for Azure AI services. Select create an Azure AI services plan. You will be taken to a page to create an Azure AI services resource. Configure it with the following settings:
Subscription: Your Azure subscription.
Resource group: Select or create a resource group with a unique name.
Region: Select the closest geographical region. If in eastern US, use “East US 2”.
Name: Enter a unique name.
Pricing tier: Standard S0.
By checking this box I acknowledge that I have read and understood all the terms below: Selected.
Select Review + create then Create and wait for deployment to complete.
Connect your Azure AI service resource to Vision Studio
Next, connect the Azure AI services resource you provisioned above to Vision Studio.

In another browser tab, navigate to Vision Studio at https://portal.vision.cognitive.azure.com.

Sign in with your account and making sure you are using the same directory as the one where you have created your Azure AI services resource.

On the Vision Studio home page, select View all resources under the Getting started with Vision heading.

The View all resource link is highlighted under Getting started with Vision in Vision Studio.

On the Select a resource to work with page, hover your mouse cursor over the resource you created above in the list and then check the box to the left of the resource name, then select Select as default resource.

Note : If your resource is not listed, you may need to Refresh the page.

The Select a resource to work with dialog is displayed with the cog-ms-learn-vision-SUFFIX Cognitive Services resource highlighted and checked. The Select as default resource button is highlighted.

Close the settings page by selecting the “x” at the top right of the screen.

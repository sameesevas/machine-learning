Open your browser console and copy and paste the code bellow, that will avoid you to get kicked off for being idle.

function ClickConnect() {
console.log("Working"); 
document
  .querySelector('#top-toolbar > colab-connect-button')
  .shadowRoot.querySelector('#connect')
  .click() 
}
setInterval(ClickConnect, 60000)

Ps. You will get kicked after 12 hours no matter what, so be sure that you are saving your progress to your Google Drive.

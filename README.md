# AppSignatureHelper
This is a helper class to generate your message hash to be included in your SMS message.

How to call this from your activity class:

AppSignatureHelper appSignatureHelper = new AppSignatureHelper(LoginActivity.this);

Log.v(TAG, appSignatureHelper.getAppSignatures().get(0));


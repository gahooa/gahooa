### Public Key

My gpg public key can be found here:

<https://raw.githubusercontent.com/gahooa/gahooa/main/jgarber%40appcove.com.asc>


To validate it:

    curl https://raw.githubusercontent.com/gahooa/gahooa/main/jgarber%40appcove.com.asc | sha256sum

... and make sure it matches:
    
    6b58cdf12985e7825a1b6dc0f1f71c21bf089e07174f3a96a0df28dd77e61fe7

To install it:

    curl https://raw.githubusercontent.com/gahooa/gahooa/main/jgarber%40appcove.com.asc | gpg --import


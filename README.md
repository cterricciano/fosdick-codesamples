# fosdick-codesamples
code samples to share with other developers integrating with Fosdick Fulfillment


To help with TokenEx integration, the below files demonstrate how to encrypt a credit card number using Bouncy Castle (https://www.bouncycastle.org/) and .NET. The encryption is openssl rsa 2048 and can also be done client side using Javascript.  An example using Javascript can be found at http://docs.tokenex.com/#browser-based-encryption
TEST_PublicKey.pem -- TokenEx's public key in PEM format.
TokenExRSA.cs -- The core file to use the encryption.
encryption_tester.zip -- Quick solution demonstrating how to use TokenExRSA.cs

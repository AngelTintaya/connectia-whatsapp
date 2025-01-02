# connectia-whatsapp

## Web Pages:
Facebook for developers:
https://developers.facebook.com/

Facebook business:
https://business.facebook.com/

## Tutorials
General Tutorial for setting up Whatsapp Cloud API
https://www.youtube.com/watch?v=NUos_GR2JuQ

Multiple tutorials for setting up Whatsapp Cloud API
https://www.youtube.com/watch?v=q0ojEbdezFU&list=PLi9cSkiBrnxYU2Efug5P6-CAK4Iu5R1Rq

Verifying Phone Number
https://www.youtube.com/watch?v=VDlyGcHlGiw

### 1. Create Whatsapp Business Page on Facebook
1.1. Create whatsapp business page on facebook

### 2. Create a "Portafolio Comercial"
2.1. Go to Facebook Business
2.2. Create a "Portafolio Comercial": Connectia Solutions

### 3. Create App
3.1. Log in to Facebook for developers
3.2. Go to My Apps
3.3. Create App: Connectia Assistant
3.4. Apps want to do: Select Others, it is for WhatsApp purpose
3.5. App Type: Business
3.6. Business Account (Portafolio Comercial): Select Connectia Solutions
3.7. Click in Create
3.8. Go to whatsapp, click set up
    (We are going to be in our main Facebook for developer page now)

### 4. Business verification
4.1. Go to Facebook Business
4.2. Click in Business Portfolio Info (Información del portafolio comercial)
4.3. Edit Business Name, if needed
4.4. Click in Business Verification Status -> View details (Will open another tab)
4.5. Click in start verification
4.6. Click in start
4.7. Select Country
4.8. Select Business Type: Private Enterprise
4.9. To be continued ....!!!!!!!!!!!!!!!!!!!!!!

-- Save a Whatsapp display name: Note, double check your legal businesss name in your "Portafolio Comercial" profile
-- Register phone:
1. Go to certify (Where you updated the whatsapp name to show)
2. Copy certify: CnoKNgjwg5bq3rjyAxIGZW50OndhIh1Bc2lzdGVudGUgVmlydHVhbCBkZSBFbWlsaWFuYVDV2sy7BhpAHAsJnkN1/7XWZJ1SgucGgU6/SI2Z6UDFpd53CHtHxr6scxCMxSWhnWwdHTzli0E2OYtTF8KPvVlBtRuKIcSfARItbQQl8uaJ0F3gQ4uzkahvK5xf5uRY7RXHineHaI0LO3PGNurMHZ2WiP9TWUcT
3. Click in follow instructions, will go to:
https://developers.facebook.com/docs/whatsapp/on-premises/reference/account#regcode


-- Ask Meta:
https://business.facebook.com/direct-support

-- Add eng language: ?locale=en_US

## Verificación de número pendiente
### Video Tutorial: https://www.youtube.com/watch?v=VDlyGcHlGiw
1. Check if phone number is not registered:
    - Go to Facebook for developers
    - Go to QuickStart (Inicio rápido)
    In WhatsApp Busines:
    - if Phone numbers is disable, PHONE NUMBER IS NOT SUSCRIBED.
    - Click in Account Information (Will open Facebook Business)
    - In our Phone Number, if it says Pendant, means our PHONE NUMBER IS NOT REGISTERED
2. Register Phone Number
    - In Facebook for developers, click on API Set Up
    - Select our Phone Number
    - Select Phone destination
    - Click Run in Postman (It will be enable after two previous point are done)
    # Postman
    - Will open Postman, Click in Fork Collection (After this point, if desired, go to postman app, recomended)
    - Click in Environments
    - Click Cloud API (We will see all our variables)
    - In User-Access-Token, paste the PERMANENT ACCESS TOKEN (In initial and current value)
    - Click in Save (Or press Ctrol + S)
    - In the right part of Cloud API tab, click Set Active (Will show when dragging the mouse upfront the tab)
        Thill will enable the variables into the Collections
    - Click in Collections
    - Click in Get Started for BSPs
    # REGISTERING PHONE NUMBER
    - Click in Step 5: Register Phone Number (After this, the Pendant state will disappear)
    - CLick in Body, define a 6 digits PIN (save it)
    - Click Save, then click in Send (Will return Success = True, if App is blocked, wait 5 - 10 minutes)
        If we refresh the facebook business page, Pendant status will disappear for our phone number
        WE CAN SEND MESSAGES NOW, but we CAN NOT RECEIVE MSSAGE YET (We need to suscribe!)
    # SUSCRIBING PHONE NUMBER
    - Click in Step 3: Suscribe to your WABA
    - Click in Send (Will return Success = True)
    - Now in Facebook for developers, Phone number should be available
3. Test sending message from our Phone Number
    - Click in Collections
    - Click in get started 
    - Click in Step 2: Send a Test Message
    - Click in Send Test Message
    - Click in Send

## Going to life
0. Remember to create a new message template for the new phone that was verified!
1. Update URL for Privacy Policy (Will redirect after clicking to Go Live, otherwise it is in App Set Up -> Basic)
2. Click to go Life
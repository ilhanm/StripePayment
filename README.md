# StripePayment
using stripe payment in asp.net


# Project

.Net Core MVC 3.1 Project to using Stripe for payment processing.


## To Install Stripe Package

with .NET CLI

```bash
dotnet add package Stripe.net --version 39.83.0
```
with Package Manager Console
```
Install-Package Stripe.net -Version 39.83.0
```

## Usage
In appsetting.jon file, you should add your own credentials where you can get from [here](https://dashboard.stripe.com/test/apikeys) .
```csharp
  "Stripe": {
    "SecretKey": "your sk",
    "PublishableKey": "your pk"
  },
```

## Screenshoots
Pay with card 
![01](https://user-images.githubusercontent.com/38858819/146416055-e0b4703d-13a9-4ae2-b133-c219c9c43205.png)
Payment details should be valid

<img src="https://user-images.githubusercontent.com/38858819/146416119-ff18a139-17fc-4afc-8b63-35e003a6a99d.png" align="left" height="450" width="470" >

<img src="https://user-images.githubusercontent.com/38858819/146416144-058ca619-a206-4c3d-9bce-1654f0fff60f.png" align="left" height="450" width="470" ><br />
<br/>

![04_redirect](https://user-images.githubusercontent.com/38858819/146416149-7aa0cf19-af79-4aaa-8f58-49a88e040b31.png)

![05_stripescreen](https://user-images.githubusercontent.com/38858819/146416154-f1eb2030-0d19-4c19-852f-cb965c4b223d.png)


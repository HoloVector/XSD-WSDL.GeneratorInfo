# XSD-WSDL.GeneratorInfo

input:
``` assembly
library generated by C# code obtained from WSDL\XSD
```

output:

``` yaml

 CreateAccountApplication: 
    Response>
     - Type: string
     - Name: AppId

    Request>
     - Type: ApplicationInfoType
     - Name: Application

     - Type: AppContactInfo
     - Name: AppContactInfo

 SendOTP: 
    Response>
     - empty
    Request>
     - Type: string
     - Name: PhoneNumber

     - Type: int
     - Name: OTP

 WelcomePack: 
    Response>
     - Type: Byte[]
     - Name: File

    Request>
     - Type: int
     - Name: formQty

     - Type: string
     - Name: employeeFullName



   -[ EXCEPTIONS ]-    
 ApplicationNotFoundException
 WrongCardException
 UnhandledException
 UserIdOrPOSNotFoundException
 UnableToParseAddressException
 ClientNotFoundException
 DataValidationException
 WrongProductException
 WrongPackageIdException
 UserBlockedException
 AgreementNotFoundException


   -[ OTHER TYPE ]-    
  Name: ApplicationInfoType
     - Name: ExternalAppId
     - Type: string

     - Name: POS
     - Type: string

     - Name: UserId
     - Type: string



  Name: SessionContextType
     - Name: POS
     - Type: string

     - Name: UserId
     - Type: string

  Name: ListOfAddressType
     - Name: Address
     - Type: List<>



  Name: ListOfAttachments
     - Name: Attachment
     - Type: List<>
```

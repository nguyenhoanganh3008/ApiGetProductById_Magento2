# ApiGetProductById_Magento2

Create folder Hoanganh in root\app\code

Install ApiGetProductById_Magento2 -> Hoanganh

Enable module Hoanganh_ApiGetProduct:

  Run:
  
  	   1, php bin/magento module:enable Hoanganh_ApiGetProduct
  
       2, php bin/magento setup:upgrade
	   
       3, php bin/magento setup:static-content:deploy -f
	   
       4, php bin/magento cache:clean

Test with Postman:


  	url : BaseUrl/rest/V2/product/getProductsById/:id
  
  
  	method : GET
  
  
  
![Capture](https://user-images.githubusercontent.com/43265454/83101854-76d35780-a0dd-11ea-809e-c09ce02f7d2b.PNG)

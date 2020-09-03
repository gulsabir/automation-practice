# Codeceptjs-skeleton
Bu projede aşağıdaki senaryoları nasıl otomatize edildiğini öğrendim.

Aşağıdaki her bir senaryoyu otomatize edildi.

Bu projede otomatize ederken uğraştırıcı kısımlar;

   1.  "Add to Cart" senaryosunun 2. adımındaki navigation bar daki "Dresses" tıklatmada ve ardından "Summer Dresses"ı Hover ederken zorlandım.
   
   2.  "Add to Cart" senaryosunun 4.adımındaki “Printed Chiffon Dress” ürününü hover edip "Add to Cart" yapmakta zorlandım.

**Scenarios**

**1.Login**
1. Go to “automationpractice.com”.
2. Click Sign In button.
3. Fill email and password fields.
4. Click Sign In button.
5. Assert that user logged in successfully

**2.Search for an Item**
1. Go to “automationpractice.com”
2. Search for “Blouse” item by using search bar.
3. Assert that item is listed in results page.


**3.Add to Cart**
1. Go to “automationpractice.com”
2. From the navigation bar navigate to Dresses > Summer Dresses
3. Assert that results are listed.
4. Add “Printed Chiffon Dress” item to cart.
5. Go to the cart.
6. Assert that “Printed Chiffon Dress” is added to the cart.

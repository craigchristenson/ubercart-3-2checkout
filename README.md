#### _For a discount on 2Checkout’s monthly fees, enter promo code:  GIT2CO  during signup._

## UberCart 3 2Checkout
----------------------------------------

This is a fork of the current 2Checkout module that is inluded in the UberCart 3 core. This fork fixes the return process issues, adds Header Redirect support and insures that demo sales are handeled correctly. 

### UberCart 3 Settings

1. Download or clone extension at https://github.com/craigchristenson/ubercart-3-2checkout
2. Extract and upload the uc_2checkout directory to /modules/ubercart/payment/ on your hosting/server. 
3. Sign in to your Drupal admin.
4. Click **Modules**.
5. Under **UberCart-Payment** activate **2Checkout** and save your changes.
6. From the admin menu click **Store**.
7. Under **Configuration** click **Payment Methods**.
8. Click **Settings**.
9. Enter your **Vendor Account Number** (2Checkout Account Number).
10. Under **Secret Word for order verification** enter your Secret Word. (Must be the same value entered on your 2Checkout Site Management page.)
11. Under **2Checkout checkout type** select either **Single page** checkout or **Multi page** checkout.
12. Click **Save Configuration**.

### 2Checkout Settings

1. Sign in to your 2Checkout account. 
2. Click the **Account** tab and **Site Management** subcategory. 
3. Under **Direct Return** select **Header Redirect**. 
4. Enter your **Secret Word**._(Must be the same value entered in your UberCart admin.)_
5. Click **Save Changes**.

**Please contact 2Checkout directly with any integration questions.**
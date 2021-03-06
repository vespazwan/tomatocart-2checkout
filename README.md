### _[Signup free with 2Checkout and start selling!](https://www.2checkout.com/referral?r=git2co)_

Integrate Tomato Cart with 2Checkout
----------------------------------------

### Tomato Cart Settings

1. Clone or Download the extension from git@github.com:craigchristenson/tomatocart-2checkout.git
2. Extract the file and upload the **admin** and **includes** folders to your Tomato Cart directory on your server.
3. In the Tomato Cart admin, click Start and under **Modules** select **Payment Methods**.
4. For **2Checkout** click the install icon and then click the edit icon.
5. For **Enable 2Checkout Payments** select **True**.
6. Under **2Checkout Seller ID**, enter your 2Checkout account number.
7. Under **2Checkout Secret Word**, enter your Secret Word. (Must be the same value entered on your 2Checkout Site Management page.)
8. For **Demo Mode** select **False** for live sales or **True** if you are testing with a demo sales.
9. For **Order Status** select something other than default such as **Processing** or **Paid**.
10. Save your changes.

### 2Checkout Settings

1. Sign in to your 2Checkout account.
2. Click the **Account** tab and **Site Management** subcategory.
3. Under **Direct Return** select **Given Links back to my Website**.
4. Set the **Approved URL** to http://www.yoursite.com/checkout.php?process (Replace http://www.yoursite.com with the actual URL to your store.)
5. Enter your **Secret Word**. (Must be the same value entered in your Tomato Cart admin.)
6. Click **Save Changes**.

**Please contact 2Checkout.com directly for integration assistance.**

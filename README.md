# FullStory Android Troubleshooting Challenge
Welcome! This repo should be used to complete the Android portion of take home challenge for the [Principal Support Engineer, Mobile Apps](https://www.fullstory.com/careers/jobs/6423283002/?gh_jid=6423283002) role.
Android Client for the example "Shoppe" app

## Getting started

1. Clone or make a fork of this repo to work locally.

#### System Requirements
- [Android Studio](https://developer.android.com/studio)

## Instructions

1. Review the customer's email and background information.
2. Determine if an escalation to engineering is necessary; draft the escalation if so.
3. Draft a response to the customer.
4. If you're able to resolve the issue, a session URL will be listed in logcat at runtime.
5. Save your draft(s) and session URL into a gist and provide a link to the gist.

### Customer's Email:
_Hello support,_

_We recently noticed a drop in the number of Android sessions in our account. We haven’t changed anything on our end since our initial deployment. One of our engineers was able to replicate the trouble and built a sample app to demonstrate the issue. You can see it on GitHub here: https://github.com/rcmaples/android-shoppe-challenge_

_We are capturing some Android sessions, but we can’t figure out why there’s been such a decrease in sessions. Please help! This is seriously impacting our reporting and metrics._

_Thanks,_

_Pam Beesly_

### Background Information:
- During a screen share with the customer, you noticed the emulator they were replicating with was running Android 13.
- Feel free to reference our [documentation for Mobile capture](https://help.fullstory.com/hc/en-us/categories/4412779509911-FullStory-for-Mobile-Apps).

---

# Misc
### Using the app

The Shoppe is a super simple e-commerce application where you can:
- Browse a list of products int the _Market_.
- Use the **Add to Cart** button to add products to your shopping cart.
- Go to your _Shopping Cart_ by clicking on the cart icon on the top right corner.
- Review your cart and then click the **Checkout** button.
- Fill out the form on the _Checkout_ view and click **Purchase**. The app persists locally all the information from this view. Please do **not** use your real information
- When clicking **Purchase** your information is validated and a Toast message will be shown. The purchase is successful if all fields passed the validate and your subtotal is greater than 0.

### App Architecture

See diagram below for the [app architecture](https://developer.android.com/jetpack/docs/guide):

![Diagram](readmeImages/diagram.jpg "App architecture diagram")

### Tips and tricks

- Checkout our [Native Mobile Privacy Rules](https://help.fullstory.com/hc/en-us/articles/360043356573-Native-Mobile-Privacy-Rules).
- For step by step guide checkout: [Getting Started Guide](https://help.fullstory.com/hc/en-us/articles/360040596093-Getting-Started-with-Android-Recording).
# Google Ad Manager Set Targeting
This repo demonstrates how to properly set custom targeting in Google Ad Manager code, also referred to as DFP or GPT tags (Google Publisher Tags). This example focuses on using GAM for the web (HTML and JS).

# Generate Google Ad Manager Tags for the Required Ad Unit(s)
Log in to [Google Ad Manager](https://admanager.google.com/). If you don’t have an account, you'll be prompted to sign up. Please note that having a Google AdSense account is required to apply for or log in to Google Ad Manager. Once logged in, navigate to **Inventory > Ad Units** to create or select an existing ad unit. After creating the ad unit, click on it and go to the **Tags** tab to generate the tags.

# Use index.html as an Example
Refer to `index.html` for guidance on how the `setTargeting` function works within Google Ad Manager and how to apply it based on your specific needs.

# Targeting Limits
It's important to note that the second argument in the `setTargeting` function should be less than 40 characters long (you can use [Word55 to check the length](https://word55.com/)). Keeping within this limit ensures the targeting values can be reported accurately in GAM reports.

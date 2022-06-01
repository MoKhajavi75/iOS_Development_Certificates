# iOS_Development_Certificates

iOS Development Certificates

## New Certificates

For new certificates archive your project using below bundle id and then change the bundle id of exported `.ipa` file:

`BundleID -> com.iapps.exportapp`

## FAQ

**Question:** What is the password?

**Answer:** `123456`

---

**Question:** How to remove old certificates?

**Answer:** Simple! Take a look at [here](https://stackoverflow.com/q/26732251/4565015).

---

**Question:** Can I use these certificates for push notifications?

**Answer:** Sadly, No!

---

**Question:** Can I use these certificates to install `.ipa` on my device?

**Answer:** You can not install `.ipa` apps on non-jailbroken devices without a valid code-signing. You should re-sign your `.ipa` with free (7 days) or paid (1 year) Apple developer account and install it on your device. These certificates are for app export only.

---

**Question:** Any documents?

**Answer:** Yep, it's [here](./guide.pdf)

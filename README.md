# iOS_Development_Certificates



## NEW METHOD - Export app

forget about certificates, use Sibapp_Export.app to export your Xcode archives easily and without any effort.
1 - download the app located in the main directory of this repository 
2 - run it
3 - select your Xcode archive (which you should archive your app normally with your code with your bundle id and Apple ID)
4 - select export and you are ready to go. thank us later


## OLD METHOD - iOS Development Certificates

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

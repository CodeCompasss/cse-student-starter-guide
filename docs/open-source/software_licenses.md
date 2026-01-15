# 📜 Understanding Software Licenses

When you create or use open-source software, **licenses** dictate what you can and cannot do with that code and how you must treat it.

Think of a license as the **"Terms and Conditions"** for code — but usually much friendlier!

---

## ❓ What is a Software License?

A software license is a legal document that governs the use or redistribution of software. In the open-source world, licenses give others permission to use your code, but often with some conditions attached.

Without a license, **nobody else has the legal right to use, copy, or distribute your code**, even if you put it on GitHub publicly!

---

## 🏎️ The MIT License
**"The 'Do Almost Anything' License"**

*   **Type:** Permissive
*   **Best for:** Simple, small projects, or when you want maximum adoption.
*   **What it says:** You can do whatever you want with this code (use it, change it, sell it), as long as you **keep the original copyright notice** and license file in your copy.
*   **Popular projects:** React, Node.js, VS Code (core).

> ✅ **Summary:** Short, simple, and very flexible.

---

## 🪶 The Apache License 2.0
**"The 'Do Anything, But With Patent Protection' License"**

*   **Type:** Permissive
*   **Best for:** Larger open-source projects, corporate-backed tools.
*   **What it says:** Similar to MIT (do whatever you want), but it adds an explicit grant of **patent rights** from contributors to users. It also requires you to document significant changes to the files.
*   **Popular projects:** Android, Apache HTTP Server, TensorFlow, Kubernetes.

> ✅ **Summary:** Like MIT, but safer for big companies and patents.

---

## 🛡️ GNU General Public License (GPLv3)
**"The 'Copyleft' or 'Share-Alike' License"**

*   **Type:** Copyleft (Protective)
*   **Best for:** Ensuring the software *stays* free and open forever.
*   **What it says:** If you base your software on GPL code and distribute it, **your software must ALSO be open source** under the same GPL license. You cannot take GPL code, modify it, close it up, and sell it as a proprietary secret.
*   **Popular projects:** Linux Kernel (GPLv2), Git, WordPress, GIMP.

> ⚠️ **Summary:** Sticky! If you use GPL code in your project, your project essentially becomes GPL too.

---

## ⚖️ Quick Comparison for Students

| License | Can I use it for private work? | Can I sell it? | Must I share my changes? | Complexity |
| :--- | :--- | :--- | :--- | :--- |
| **MIT** | ✅ Yes | ✅ Yes | ❌ No | Low |
| **Apache 2.0** | ✅ Yes | ✅ Yes | ❌ No | Medium |
| **GPLv3** | ✅ Yes | ✅ Yes | ✅ **Yes** (if distributed) | High |

---

## 🧠 Which one should I choose?

*   **For most student projects:** Go with **MIT**. It's simple and encourages people to use your code.
*   **If you care about patents:** Use **Apache 2.0**.
*   **If you believe code should always remain free:** Use **GPL**.

👉 *Check out [ChooseALicense.com](https://choosealicense.com/) for a non-lawyer explanation of every license.*
# 🌸 Sakuraa Mail Forward ✉️

This repository manages forwarding rules for `@sakuraa.org` email addresses.

Once your rule is merged, your sakuraa mailbox will gently forward letters to your real inbox 🌷

---

## 🌼 How to Join

### 1️⃣ Create Your File

Create a file inside:

```
./Sakuraa-Mail/<YourName>
```

Example:

```
./Sakuraa-Mail/Ayachi
```

---

### 2️⃣ Add Your Forwarding Rule

Inside the file, write:

```
yourname@sakuraa.org -> your-email@example.com
```

Example:

```
ayachi@sakuraa.org -> ayachi@gmail.com
```

After your Pull Request is merged, mail sent to your sakuraa address will bloom into your real inbox 🌸

---

## 🔐 Want to Keep Your Email Private?

If you don’t want to expose your real email address publicly, you can encrypt your file using GPG ✨

### 🌿 Encrypt with:

```bash
gpg -a -e -r BE4D7900948C2990 Ayachi
```

This will generate:

```
Ayachi.asc
```

---

## 📂 File Naming Rules (Very Important 🌷)

* 🌸 **Encrypted file** → use `.asc`

  ```
  Ayachi.asc
  ```

* 🌼 **Not encrypted** → use plain filename

  ```
  Ayachi
  ```

Please follow this rule carefully so the system can recognize your file correctly.

---

## 🔏 Please Sign Your Commits 💌

For security and authenticity, we kindly recommend signing your commits with GPG before submitting your Pull Request.

Example:

```bash
git commit -S -m "Add mail forward for Ayachi"
```

Signed commits help protect the sakuraa garden from unwanted changes 🌿

---

## 🚫 Reserved Names

Some addresses are protected and cannot be registered:

```
admin@
postmaster@
mail@
my@
```

Please choose another lovely name 🌺

---

## 📮 Service Notice

* 🌸 This is a **forward-only** service.
* 📤 Sending mail from `@sakuraa.org` is currently not supported.
* ✨ Outgoing mail support may bloom in the future.
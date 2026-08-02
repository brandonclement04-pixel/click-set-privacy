# Click Set — Privacy Policy

**Effective date:** August 2, 2026
**Last updated:** August 2, 2026

Click Set is a click-track and guide-vocal app for worship teams, published by **Brandon Clement**
("we", "us"). This policy explains what the app and the Click Set Web Player do with your
information.

The short version: Click Set works locally on your device by default. Nothing leaves your device
unless you connect Planning Center or use the Web Player. We don't track you, show ads, use
analytics, or sell anything about you to anyone.

> **Note on earlier versions of this policy.** Before August 2026 this policy said Click Set stored
> data only on your device and did no server-side collection. That was accurate at the time. The Web
> Player feature, added in July 2026, uploads audio to servers we operate when you choose to use it.
> Section 3 describes exactly what that involves.

---

## 1. What stays on your device

Everything you create in Click Set — setlists, songs, arrangements, tempos, section maps, reference
recordings you import, vocal-removed versions, alternate key recordings, MIDI profiles, themes, and
app settings — is stored **only on your device**, in the app's private storage. We cannot see it,
and it is not uploaded anywhere unless you take one of the actions described below.

Audio exports you create are saved wherever you choose to save them, and are not sent to us.

---

## 2. Planning Center (optional)

If you connect a Planning Center Online account, the app uses Planning Center's official API to read
your service plans, songs, arrangements, and any audio attachments you choose to download.

- Your Planning Center **login credentials are never seen by us**. Sign-in happens through Planning
  Center's own authorization page.
- The resulting access tokens are stored in your device's **Keychain** and used only to talk to
  Planning Center on your behalf. **They are never sent to us or to anyone else.**
- Plan and song information downloaded from Planning Center is stored **locally on your device**.
- The app also reads **your display name** from your Planning Center account, purely so it can show
  which account is connected. It is stored on your device and is never transmitted to us.
- Disconnecting your account in Settings deletes those tokens from your device.

Your use of Planning Center remains governed by Planning Center's own privacy policy.

---

## 3. The Click Set Web Player (optional)

If you use **Send to Web Player**, the app renders audio for the selected setlist and uploads it to
servers we operate, so that people you share the link with can listen in a web browser.

**This is the only feature that sends your content to us, and it never runs on its own — it happens
only when you tap it.**

### What is uploaded

- **Audio files** the app generates for each song: the click-and-guide track, and — where you have
  one — the reference recording and its vocal-removed version.
- **Setlist information**: song titles, tempo, time signature, song order, duration, and the service
  date associated with the setlist.
- **An Apple subscription identifier** (your original transaction ID), used to confirm you have an
  active Click Set Pro purchase before we accept an upload.

We do not upload your Planning Center tokens or the data fetched from Planning Center, your other
setlists, your MIDI profiles, your settings, or anything else from the app.

### How the subscription identifier is handled

- It is **sent to our server** with each upload and used to ask Apple's App Store Server API whether
  the purchase is valid.
- A successful check is held **in memory for up to 10 minutes** so that repeated uploads in a single
  publishing session don't re-query Apple. It is not written to a database or a log file.
- What we **store** is a **one-way hash** of it (HMAC-SHA-256 with a secret key), used as the name of
  the folder your files live under. The identifier cannot be recovered from that folder name, and it
  does not identify you to us by name, email, or Apple ID.

### Who can access what you publish

**Links are unlisted, not private.** Anyone who has a Web Player link can open it and listen without
an account, an app, or a password. Treat a link exactly as you would treat the audio files
themselves. Do not post one anywhere you would not post the recordings.

### How long it is kept

Published audio stays on our servers until:

- you publish that setlist again — older files no longer referenced are deleted automatically; or
- you ask us to delete it (see Section 8); or
- we remove it under our Terms of Service.

There is a storage limit of 2 GB per subscriber.

### Where it is stored

On infrastructure operated by **Cloudflare, Inc.** across their global network, under our account.
The storage is private; files are reachable only through the unlisted link.

### Listener information

When someone opens a Web Player link, our servers handle the request the way any web server does,
which necessarily involves the IP address the request came from. We do not use cookies, analytics,
advertising identifiers, or any tracking technology in the Web Player, and we do not build profiles
of listeners. A listener's volume and theme choices are stored **in that person's own browser** and
are never sent to us.

---

## 4. Purchases and subscriptions

Click Set Pro is sold through the **Apple App Store**. Apple processes all payments. We never receive
or store your payment details, card numbers, or billing address.

To confirm an active purchase for Web Player publishing, our server checks with Apple's App Store
Server API using the subscription identifier described in Section 3.

---

## 5. What we do not do

- We do not track you across apps or websites.
- We do not use advertising, analytics, or crash-reporting SDKs. There are none in the app.
- We do not sell, rent, or share your information with data brokers or advertisers.
- We do not build user profiles.
- We do not access your microphone, camera, contacts, photos, or location.
- We do not ask for your name, email address, phone number, or postal address.

---

## 6. Service providers

We rely on a small number of providers strictly to deliver the features above:

| Provider | Purpose |
|---|---|
| Apple | App distribution, purchases, subscription verification |
| Cloudflare, Inc. | Hosting and delivery of Web Player audio and pages |
| Planning Center Online | Only if you choose to connect your own account |

---

## 7. Children

Click Set is a tool for worship and music teams and is not directed to children under 13. We do not
knowingly collect personal information from children under 13.

---

## 8. Your choices and requests

- **Stop publishing:** simply don't use Send to Web Player. Nothing is uploaded otherwise.
- **Delete published audio:** email **brandonclement06@icloud.com** with the Web Player link and we
  will delete the associated files.
- **Disconnect Planning Center:** Settings → Planning Center → Disconnect. Tokens are deleted from
  your device immediately.
- **Delete everything local:** deleting the app removes all local data. This cannot be undone.

Depending on where you live, you may have additional rights to access, correct, or delete personal
information, or to request a copy of it. Contact us at **brandonclement06@icloud.com** and we will
respond as required by applicable law.

---

## 9. Copyright

The Web Player hosts audio you supply. You are responsible for holding the rights to the recordings
you upload and share — see our Terms of Service. If you believe material hosted by us infringes your
copyright, contact **brandonclement06@icloud.com**.

---

## 10. Security

Data in transit is protected with TLS. Planning Center tokens are stored in the device Keychain.
Published files are held in private storage reachable only through their unlisted link, and access to
our hosting account is restricted to us. No system is perfectly secure and we cannot guarantee
absolute security — in particular, remember that **Web Player links are unlisted rather than
protected**.

---

## 11. Changes to this policy

If we make material changes we will update the date at the top and, where appropriate, note the
change in the app or on our website.

---

## 12. Contact

**Brandon Clement**
Email: **brandonclement06@icloud.com**

---

[Terms of Service](./terms) · [Support](./support)

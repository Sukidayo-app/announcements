---
layout: default
title: FAQ
lang: en
---
<style>
  .page-title { font-size: 24px; font-weight: 700; margin-bottom: 20px; }
  .toc { background: #fafafa; border: 1px solid #e8e8e8; border-radius: 10px; padding: 20px 24px; margin-bottom: 32px; }
  .toc-title { font-size: 14px; font-weight: 700; margin-bottom: 10px; color: #666; }
  .toc ul { list-style: none; padding-left: 0; margin: 0; }
  .toc li { font-size: 14px; margin-bottom: 4px; }
  .toc a { color: #EE8514; text-decoration: none; }
  .toc a:hover { text-decoration: underline; }
  .toc > ul > li { margin-bottom: 2px; }
  .toc details > summary {
    font-size: 14px; font-weight: 600; color: #EE8514; cursor: pointer;
    list-style: none; padding: 5px 0; display: flex; align-items: flex-start; gap: 7px;
  }
  .toc details > summary::-webkit-details-marker { display: none; }
  .toc details > summary::before {
    content: "\25B6"; font-size: 9px; line-height: 2.1; color: #EE8514;
    flex: 0 0 auto; transition: transform .15s ease;
  }
  .toc details[open] > summary::before { transform: rotate(90deg); }
  .toc details > summary:hover { text-decoration: underline; }
  .toc details > ul { padding-left: 20px; margin: 2px 0 10px; }
  .toc details > ul > li { font-size: 13.5px; margin-bottom: 7px; line-height: 1.55; }
  .toc details a { color: #555; }
  .toc details a:hover { color: #EE8514; }
  .faq-body h2, .faq-body h3 { scroll-margin-top: 16px; }
  .faq-body h2 { font-size: 18px; font-weight: 700; margin: 32px 0 12px; padding-bottom: 8px; border-bottom: 2px solid #f0f0f0; }
  .faq-body h3 { font-size: 16px; font-weight: 700; margin: 20px 0 6px; color: #EE8514; }
  .faq-body h3::before { content: "Q. "; }
  .faq-body h3 + p::before { content: "A. "; font-weight: bold; }
  .faq-body p { font-size: 15px; margin-bottom: 12px; }
  .faq-body ul, .faq-body ol { padding-left: 24px; margin-bottom: 12px; font-size: 15px; }
  .faq-body li { margin-bottom: 4px; }
  .faq-body a { color: #EE8514; }
  .faq-body blockquote { background: #f5f5f5; border-left: 4px solid #EE8514; padding: 12px 16px; border-radius: 4px; margin-bottom: 12px; font-size: 14px; }
  .faq-body table { border-collapse: collapse; width: 100%; margin-bottom: 16px; font-size: 14px; }
  .faq-body th, .faq-body td { border: 1px solid #eee; padding: 8px 12px; }
  .faq-body th { background: #f9f9f9; }
  @media (max-width: 600px) {
    .page-title { font-size: 20px; }
    .toc { padding: 16px 18px; }
    .toc details > summary { font-size: 13.5px; }
    .toc details > ul > li { font-size: 13px; }
    .faq-body h2 { font-size: 16px; }
    .faq-body h3 { font-size: 15px; }
    .faq-body p, .faq-body ul, .faq-body ol { font-size: 14px; }
    .faq-body table { display: block; overflow-x: auto; -webkit-overflow-scrolling: touch; }
  }
</style>

<div class="page-title">FAQ</div>
{% include lang-tabs.html section="faq" lang="en" %}

<div class="toc">
  <div class="toc-title">📖 Contents</div>
  <ul>
    <li>
      <details>
        <summary>🐾 Getting Started</summary>
        <ul>
          <li><a href="#q-how-to-start">How do I get started?</a></li>
          <li><a href="#q-change-profile">Can I change my name, gender, or animal's name later?</a></li>
          <li><a href="#q-no-notifications">I'm not receiving notifications. How do I fix this?</a></li>
          <li><a href="#q-no-questions">I'm not receiving questions. What should I do?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>📝 Q&amp;A, Couple Quizzes &amp; Answers</summary>
        <ul>
          <li><a href="#q-see-results">How do I see the results?</a></li>
          <li><a href="#q-edit-answer">I answered by mistake. Can I redo it?</a></li>
          <li><a href="#q-comment-notification">Will my partner be notified when I comment on an answer?</a></li>
          <li><a href="#q-partner-only-question">My partner received the latest question but I didn't. What should I do?</a></li>
          <li><a href="#q-past-answers-missing">My past answers and results disappeared. What should I do?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>📷 Our Memories</summary>
        <ul>
          <li><a href="#q-memory-when">When can I start adding this month's memory?</a></li>
          <li><a href="#q-memory-edit">Can I edit a memory I already added?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>🛠 Settings &amp; Features</summary>
        <ul>
          <li><a href="#q-delivery-time">Can I change the question delivery time?</a></li>
          <li><a href="#q-logout">How do I log out?</a></li>
          <li><a href="#q-transfer-data">How do I transfer my data to a new device?</a></li>
          <li><a href="#q-fresh-start-screen">I signed in after a device change but it's starting from scratch. Why?</a></li>
          <li><a href="#q-cohabitation">Can I change my cohabitation status?</a></li>
          <li><a href="#q-future-anniversary">Can I set a future date for an anniversary?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>📅 Anniversaries</summary>
        <ul>
          <li><a href="#q-fixed-anniversary">Some anniversaries can't be deleted or renamed. Why?</a></li>
          <li><a href="#q-anniversary-order">I want to change the order of my anniversaries.</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>💌 Message Cards</summary>
        <ul>
          <li><a href="#q-card-edit">Can I edit or delete a message card that has already been sent?</a></li>
          <li><a href="#q-card-timezone">My partner and I live far apart. What time zone is used for the message card delivery time?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>🚪 Account Deletion &amp; Unpairing</summary>
        <ul>
          <li><a href="#q-delete-account">How do I delete my account?</a></li>
          <li><a href="#q-unpair">How do I unpair from my partner?</a></li>
          <li><a href="#q-partner-deleted">What happens if my partner deletes their account?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>💳 Subscription</summary>
        <ul>
          <li><a href="#q-sub-features">What features are included in the subscription?</a></li>
          <li><a href="#q-sub-both">Do both partners need a subscription?</a></li>
          <li><a href="#q-sub-cancel">How do I cancel my subscription?</a></li>
          <li><a href="#q-sub-cancel-timing">Will premium features stop immediately after cancelling?</a></li>
          <li><a href="#q-sub-after-cancel">Will I lose access to paid features I used (like Couple Quiz answers or added "Things I Want to Do" categories) after canceling?</a></li>
          <li><a href="#q-sub-device-change">If I change my device during the subscription period, will the subscription carry over?</a></li>
          <li><a href="#q-sub-not-working">I'm subscribed but premium features aren't working. Why?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>🎁 Decorations &amp; Surprises</summary>
        <ul>
          <li><a href="#q-furniture-unlock">How do I unlock more furniture and items?</a></li>
          <li><a href="#q-furniture-countdown">The countdown to new furniture has disappeared. Why?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>❓ Other</summary>
        <ul>
          <li><a href="#q-skip-question">What if a question feels too hard or I'm just not in the mood?</a></li>
          <li><a href="#q-ads">I saw an unpleasant ad. Can you do something about it?</a></li>
        </ul>
      </details>
    </li>
  </ul>
</div>

<div class="faq-body" markdown="1">

## 🐾 Getting Started {#getting-started}

### How do I get started? {#q-how-to-start}

Here's how to get started:

**For the person sending the invite:**
1. Sign in and tap "Start fresh"
2. Enter your profile and choose your animal
3. Answer the first question
4. Invite your partner
5. After the tutorial, questions will be delivered to both of you at a set time 💌

**For the person who received the invite:**
1. Tap "Start with invite code" and enter the code
2. Enter your profile and choose your animal
3. Answer the first question
4. After the tutorial, questions will be delivered to both of you at a set time 💌

### Can I change my name, gender, or animal's name later? {#q-change-profile}

Yes — all can be changed from My Page (top-right menu icon) → Settings → Basic Settings. Note: the animal type and color cannot be changed.

### I'm not receiving notifications. How do I fix this? {#q-no-notifications}

Notifications may not be enabled. Please go to your device settings and turn on app notifications for Riamo.

### I'm not receiving questions. What should I do? {#q-no-questions}

Your partner may not have answered yet. The next question is sent at the scheduled delivery time once both of you have answered. Please check whether both of you have submitted your answers.

---

## 📝 Q&A, Couple Quizzes & Answers {#questions}

### How do I see the results? {#q-see-results}

Results are shown once both of you have answered. If you answer first, your partner's answer will be hidden until they respond.

### I answered by mistake. Can I redo it? {#q-edit-answer}

Only Q&A answers can be edited. Couple quiz answers cannot be changed. You can use the comment feature or talk it over in person.

### Will my partner be notified when I comment on an answer? {#q-comment-notification}

Yes, they'll receive a push notification. A red badge will also appear inside the app.

### My partner received the latest question but I didn't. What should I do? {#q-partner-only-question}

We've confirmed cases where only one partner receives the next question despite both having answered. This may be a bug — please contact us via Menu → Contact Us.

### My past answers and results disappeared. What should I do? {#q-past-answers-missing}

This can happen temporarily due to network congestion. Try reopening the app after some time. If the issue persists after a day, please contact us.

---

## 📷 Our Memories {#memories}

### When can I start adding this month's memory? {#q-memory-when}

You can upload memories for the current month starting from the 1st of each month. Use the + button in Our Records → Memories tab to add them. A banner also appears on the home screen from the 25th at 12:00 until the 3rd of the following month at 23:59.

### Can I edit a memory I already added? {#q-memory-edit}

You can edit the photos and the "memory note." Go to Our Records → Memories, select the memory, and tap the edit icon (pencil) in the top right. Comments cannot be edited.

---

## 🛠 Settings & Features {#settings}

### Can I change the question delivery time? {#q-delivery-time}

Only the person who sent the invite can change this. It can be set in 1-hour increments and applies to both partners. Go to My Page (top-right menu icon) → Settings → Basic Settings → Question Delivery Time.

### How do I log out? {#q-logout}

Go to My Page (top-right menu icon) → Other → Log Out. After the confirmation screen, the app will return to the startup screen.

### How do I transfer my data to a new device? {#q-transfer-data}

You can transfer your data by logging in with the same account you used on your previous device. If you log in with a different account, it will be treated as a new account, and your previous data will not be carried over.

- If you signed in using Google, please log in with the same Google account on both devices
- If you signed in using Apple, please log in with the same Apple ID on both devices

[Reference: If I change my device during the subscription period, will the subscription carry over?](#subscription)

### I signed in after a device change but it's starting from scratch. Why? {#q-fresh-start-screen}

If you sign in with a different account from the one you were using before, the tutorial will start as if you are a new user.

If you sign in with the same account you used previously, the Riamo home screen should appear immediately after signing in. If the home screen does not appear, you may be signed in with a different account. Please try signing in with another account.

If you accidentally started with a new account, please log out or delete the account from the three-dot menu (…) in the upper-right corner of the tutorial screen, confirm which account you should be using, and then sign in again.

### Can I change my cohabitation status? {#q-cohabitation}

Yes, you can change it by following the steps below.

My Page (gear icon in the upper right) → Menu → Basic Settings → Partner Info → Cohabitation Status

From the next scheduled delivery time after the change, you will receive questions matching your new cohabitation status.

### Can I set a future date for an anniversary? {#q-future-anniversary}

Sorry, future dates are not supported at this time.

---

## 📅 Anniversaries {#anniversary}

### Some anniversaries can't be deleted or renamed. Why? {#q-fixed-anniversary}

The following four anniversaries are created automatically as default entries and cannot be deleted or renamed: Dating Anniversary, Your Birthday, Your Partner's Birthday, and the Day You Started Riamo.

### I want to change the order of my anniversaries. {#q-anniversary-order}

Anniversaries are automatically sorted by the nearest upcoming date and cannot be reordered manually.

---

## 💌 Message Cards {#message-card}

### Can I edit or delete a message card that has already been sent? {#q-card-edit}

Sent message cards cannot be edited or deleted. Scheduled cards can be edited or deleted before they are delivered.

### My partner and I live far apart. What time zone is used for the message card delivery time? {#q-card-timezone}

The scheduled delivery time is based on the recipient's time zone. For example, if you set it to 8:00, the card will arrive at 8:00 in your partner's local time.

---

## 🚪 Account Deletion & Unpairing {#account}

### How do I delete my account? {#q-delete-account}

In Riamo, you can delete your account directly from within the app:

My Page (top-right menu icon) → Settings → Account Management → Delete Account

Please note that once your account is deleted, all of your answer data will also be deleted and cannot be restored. Also, subscriptions are not automatically canceled. Please complete the cancellation process separately.

[Related: How do I cancel my subscription?](#subscription)

### How do I unpair from my partner? {#q-unpair}

Riamo is designed to be used as a paired service, so we do not provide an option to "unpair" accounts. Instead, we guide users to delete their account.

Related:
- [What happens if my partner deletes their account?](#account)
- [How do I delete my account?](#account)

### What happens if my partner deletes their account? {#q-partner-deleted}

Riamo is designed for use in pairs. After your partner deletes their account, you cannot use the service alone.

When your partner deletes their account, a notification will appear on your screen informing you and requesting your approval to delete your own account.

For example, in the case of a couple A and B:
- Person A deletes their account
- A notification appears on B's Riamo screen informing them of A's account deletion and requesting B's consent to delete their own account, as the service can no longer be used

---

## 💳 Subscription {#subscription}

### What features are included in the subscription? {#q-sub-features}

The following features are included:

- Ad-free experience
- Monthly tickets to unlock Couple Quiz themes
- Wish List customization (add, edit, delete categories)
- More photos available for the monthly "Our Memories"
- More memories you can register for completed Wish List items

Riamo is currently available as a beta version, and we are continuing to review subscription features based on user feedback as we work toward the official release. If there are any features you would like to see, please feel free to share your feedback through the in-app feedback box.

### Do both partners need a subscription? {#q-sub-both}

No — if either one subscribes, both can enjoy premium features.

### How do I cancel my subscription? {#q-sub-cancel}

Cancellation must be done through Google Play or the App Store, not within the Riamo app. For details, please check below.

- [Canceling, pausing, or changing a Google Play subscription (Google Play Help Center)](https://support.google.com/googleplay/answer/7018481)
- [How to cancel a subscription on Apple (Apple Support)](https://support.apple.com/en-us/118428)

### Will premium features stop immediately after cancelling? {#q-sub-cancel-timing}

No — even if you cancel mid-term, you can continue using premium features until the next renewal date. Example: For a subscription valid until 7/31, canceling on 7/29 allows use until the 31st.

### Will I lose access to paid features I used (like Couple Quiz answers or added "Things I Want to Do" categories) after canceling? {#q-sub-after-cancel}

Couple Quizzes you've already unlocked will remain accessible after cancellation, and any tickets you still hold will not expire when you cancel. However, categories added to your "Things I Want to Do" list during your subscription will no longer be viewable after cancellation. After cancellation, the to-do list items within the added categories will be hidden.

### If I change my device during the subscription period, will the subscription carry over? {#q-sub-device-change}

Subscription information is linked to the App Store/Google Play account used at purchase, not your Riamo login account. After changing devices, log in to the App Store / Google Play with the same account used for purchase, then try selecting [Restore Purchase] on the subscription purchase screen.

※ Subscriptions cannot be transferred between different operating systems (Android → iOS / iOS → Android). In that case, please cancel the subscription in the store where you originally purchased it, then purchase it again from the store for your new OS.

- [Cancel on Google Play](https://support.google.com/googleplay/answer/7018481)
- [Cancel on App Store](https://support.apple.com/en-us/118428)

### I'm subscribed but premium features aren't working. Why? {#q-sub-not-working}

Subscription information is linked to the App Store/Google Play account used at purchase, not your Riamo login account. Please verify that the store account is the one subscribed to the service. If you are using the account that subscribed but still cannot access paid features, please contact support via My Page (top-right menu icon) → [Contact Us].

---

## 🎁 Decorations & Surprises {#fun}

### How do I unlock more furniture and items? {#q-furniture-unlock}

New furniture is added as you and your partner answer the questions together. You can check how many questions away the next piece of furniture is in the "X questions until next furniture" counter on the home screen.

### The countdown to new furniture has disappeared. Why? {#q-furniture-countdown}

Currently, furniture acquisition ends once you have answered a set number of questions. When you have obtained all available furniture, the countdown will no longer appear.

Please note that a redesign is planned for the future, which will include changes to furniture and item placement and how they are obtained.

---

## ❓ Other {#other}

### What if a question feels too hard or I'm just not in the mood? {#q-skip-question}

No worries — you don't have to answer. A casual "let's try again tomorrow" is totally fine! Go at your own pace.

### I saw an unpleasant ad. Can you do something about it? {#q-ads}

We sincerely apologize for any discomfort caused. We have blocking settings in place to prevent ads from inappropriate categories. However, when the advertised app itself is distributed as a security tool or AI tool, for example, we may not always be able to detect in advance if the ad content uses alarming or misleading language. If you encounter a malicious ad, please take a screenshot and contact us through the inquiry form.

Please note that ads and in-app purchases help us maintain stable operations and continue developing new features. We appreciate your understanding.

---

## 📮 Still need help?

Feel free to reach out via Menu → Contact Us.

</div>

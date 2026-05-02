# Project Setup (Boilerplate)

## Boilerplate

Use a boilerplate so you do not rebuild the same foundation for every new app.

A boilerplate can be:

- A personal boilerplate you have used before.
- An iOS boilerplate.
- An Android boilerplate.
- A Flutter boilerplate.
- A React Native boilerplate.
- A starter kit that already supports monetization.

The main goal is to ship faster and avoid repeating basic setup work.

## What The Boilerplate Should Include

Minimum boilerplate setup:

- Core dependencies.
- Project folder structure.
- Onboarding.
- Paywall.
- Payment.
- Free trial.
- Premium state.
- Settings page.
- App config.
- Base theme.
- Reusable components.

## Dependencies

Prepare dependencies that are used in most apps.

Examples:

- Navigation.
- State management.
- In-app purchase.
- Subscription.
- Analytics.
- Crash reporting.
- Remote config.
- Image picker or camera.
- API client.
- Local storage.

The goal is to make every new project ready to build without starting from zero.

## Onboarding

Onboarding should already exist as a base flow.

Onboarding content:

- Short intro to the app.
- Main app benefit.
- Permission request if needed.
- Route user to the paywall or main screen.

Onboarding does not need to be rebuilt from scratch for every app. Prepare a template where copy, icons, colors, and images can be changed quickly.

## Paywall

Paywall should already exist in the boilerplate if the app uses subscription monetization.

Minimum paywall content:

- Benefit headline.
- Premium feature list.
- Pricing options.
- Continue button.
- Restore purchase.
- Terms and privacy links.
- Free trial if available.

The paywall content should be easy to replace for each app.

## Payment & Trial

Payment setup should be reusable.

Prepare:

- Product ID.
- Subscription package.
- Trial status.
- Purchase flow.
- Restore purchase.
- Premium access check.
- Error handling for failed purchases.

Make sure the app can separate free users from premium users.

## Premium State

Prepare logic for checking premium status.

Example needs:

- Whether the user is subscribed.
- Whether the trial is still active.
- Whether a premium feature can be opened.
- Whether the paywall should be shown.
- Whether the subscription has expired.

Premium state should be usable across all screens.

## Settings Page

Minimum settings page:

- Restore purchase.
- Manage subscription.
- Privacy policy.
- Terms of use.
- Contact support.
- App version.

If the app has user accounts, add:

- Profile.
- Sign out.
- Delete account.

## Project Structure

Use a consistent folder structure.

Example:

```text
app/
  screens/
  components/
  services/
  config/
  constants/
  utils/
  assets/
```

For a new app, only replace:

- App name.
- Icon.
- Theme.
- Copywriting.
- Main feature.
- Product ID.
- Metadata.

## Step-by-Step

### 1. Clone The Boilerplate

Start from a ready boilerplate.

Do not start from an empty project unless it is truly necessary.

### 2. Rename The Project

Rename the project for the new app.

Update:

- App name.
- Bundle ID.
- Package name.
- App icon.
- Splash screen.
- Product ID.

### 3. Set Up Dependencies

Make sure all dependencies are installed and the project can run.

Check:

- App can run.
- No dependency errors.
- Build succeeds.
- Navigation works.
- Theme renders correctly.

### 4. Set Up Onboarding

Replace onboarding content for the app.

Update:

- Headline.
- Description.
- Benefit.
- Image or icon.
- Permission request if needed.

### 5. Set Up Paywall

Replace the paywall based on the app positioning.

Update:

- Premium benefits.
- Subscription package.
- Free trial.
- Product ID.
- Pricing display.

### 6. Set Up Premium Access

Connect the main feature with premium state.

Examples:

- Free users can only scan a limited number of times.
- Premium users get unlimited access.
- Certain features are locked until the user subscribes.

### 7. Set Up Settings

Make sure the settings page is ready.

Check:

- Restore purchase works.
- Privacy policy opens.
- Terms of use opens.
- Contact support is available.
- App version is visible.

### 8. Run The App

Run the app and check the base flow.

Checklist:

- Onboarding appears.
- Paywall appears.
- Main screen opens.
- Settings page opens.
- Premium state is detected.
- No crash on first launch.

## Summary

Project setup should start from a boilerplate that already includes dependencies, onboarding, paywall, payment, trial, premium state, and settings, so the main focus can move directly to the app's core feature.

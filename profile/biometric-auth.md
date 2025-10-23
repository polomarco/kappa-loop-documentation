# Biometric Authentication

Kappa Loop supports biometric authentication for quick and secure sign-in using Face ID, Touch ID, or fingerprint.

## What is Biometric Authentication?

Biometric authentication allows you to sign in to the app using your device's built-in security features instead of typing your password each time.

**Supported Methods:**
* **Face ID** (iPhone/iPad with Face ID)
* **Touch ID** (iPhone/iPad with Touch ID)
* **Fingerprint** (Android devices with fingerprint sensor)

## Setting Up Biometric Authentication

There are two ways to enable biometric authentication:

### Option 1: During First Login (Recommended)

After you sign in with your password for the first time, the app will prompt you:

1. A dialog appears asking "Enable [Face ID/Fingerprint]?"
2. Tap **Enable** to set it up now, or **Not Now** to skip
3. If you choose Enable, authenticate with your biometric method
4. Your credentials are securely stored on your device
5. You'll see a success message confirming it's enabled

### Option 2: From Settings

You can enable biometric authentication anytime from your profile:

1. Go to your **Profile** (via the floating action button)
2. Tap **Privacy & Security**
3. Find the **Biometric Authentication** section
4. Toggle the switch to **On**
5. Authenticate with your biometric method when prompted
6. Your credentials are securely stored

## Using Biometric Authentication

Once enabled, signing in is quick and easy:

1. Open the **Kappa Loop** app
2. Tap **Sign in with [Face ID/Fingerprint]** button
3. Authenticate using your biometric method
4. You're signed in automatically

💡 **Tip**: You can always tap "Use Password Instead" if you prefer to sign in with your password.

## Disabling Biometric Authentication

To turn off biometric authentication:

1. Go to your **Profile**
2. Tap **Privacy & Security**
3. Find the **Biometric Authentication** section
4. Toggle the switch to **Off**
5. Your stored credentials are securely deleted

## Security & Privacy

Your security is our priority:

* **Biometric data never leaves your device** - All biometric authentication is handled by your device's operating system
* **Encrypted storage** - Your credentials are encrypted using your device's secure storage:
  * iOS: Stored in Keychain with device-level encryption
  * Android: Stored in EncryptedSharedPreferences
* **On-device only** - Your biometric information is never sent to our servers
* **Easy to disable** - You can turn off biometric authentication anytime from settings

## Troubleshooting

### "Biometric Authentication Not Available"

This message appears if:
* Your device doesn't have biometric hardware
* Biometric authentication is disabled in your device settings
* You haven't set up Face ID, Touch ID, or fingerprint on your device

**Solution**: Go to your device Settings and set up Face ID, Touch ID, or fingerprint first.

### "Authentication Failed"

This happens when the biometric scan doesn't match:
* Try again with better positioning
* Make sure your face/finger is clean and clearly visible
* Use "Use Password Instead" if the issue persists

### "Locked Out"

After too many failed biometric attempts:
* Your device may temporarily disable biometric authentication
* Use your password to sign in
* Wait a few minutes before trying biometric authentication again

### Biometric Button Doesn't Appear

If you don't see the biometric sign-in button:
* Make sure you've enabled it in Privacy & Security settings
* Verify your device supports biometric authentication
* Check that you've enrolled at least one biometric method on your device

## Requirements

To use biometric authentication, you need:

* ✅ A device with Face ID, Touch ID, or fingerprint sensor
* ✅ Biometric authentication set up in your device settings
* ✅ An active Kappa Loop account

## Frequently Asked Questions

### What happens if I log out?

When you log out, your session ends but your biometric credentials remain stored on your device. This allows you to quickly sign back in using biometric authentication.

To completely remove your credentials, disable biometric authentication in settings before logging out.

### Can I use biometric authentication on multiple devices?

Yes! You need to set up biometric authentication separately on each device. Your credentials are stored locally on each device and never synced between devices.

### Is biometric authentication required?

No, biometric authentication is completely optional. You can always sign in using your password.

---

_Last updated: October 2025_

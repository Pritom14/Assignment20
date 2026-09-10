# Assignment20

This assignment covers how to generate a signed APK for an Android application
using IntelliJ IDEA or Android Studio.

## Generating a Signed APK

1. Open the **Build** menu and select **Generate Signed APK**.
2. In the dialog, choose a keystore:
   - If you don't have one yet, click **Create new...**.
   - Choose a folder and file name for the new `.jks` keystore file, then set a
     keystore password.
3. Fill in the key details for your application: **Alias**, **Key password**,
   and validity/certificate information such as your name and organization.
4. Click **Next**.
5. Choose whether to enable **ProGuard** code shrinking/obfuscation for the
   build.
6. Click **Finish**.

Your signed APK will be generated and ready for distribution.

## Notes

- Keep your keystore file and passwords safe and backed up — you'll need the
  same keystore to publish future updates to the same app.
- See the [`assignment`](./assignment) file for the original assignment notes.

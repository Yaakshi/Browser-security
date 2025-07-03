# Browser-security

## Identify and Remove Suspicious Browser Extensions

I use Brave browser. These are the extensions that I have:

![image](https://github.com/user-attachments/assets/6052996f-2740-4226-bb06-ac1f94d421f5)

- Only one extension is switched on.
- We need not worry much about other extensions because they are already disabled.
  
- Let us analyse the Google Docs Offline Extension.

![image](https://github.com/user-attachments/assets/17545a88-38db-41b3-8c4b-69fd72471283)

- It has direct access to my Google Docs and Google Drive.
- The extension was added to my browser by a third party source (it is not confirm that it was installed by Google).
- Let us analyse the site settings to get further insight on the permissions that the extension holds.
  - 20/33 permissions are set to Ask(default).
  - 8/33 permissions are set to Allow.
    - Autoplay
    - Javascript
    - Images
    - Popups and redirects
    - Automatic downloads
    - v8 optimiser
    - Payment handlers
    - Protected content IDs
  - The rest are blocked.

![image](https://github.com/user-attachments/assets/f698120c-30c9-4de2-a37b-0d2afc04a83d)
- If I were to install an extension, I mostly use chrome web store.
- I do not remember installing from any external source.
- I cannot find the extension in the store.
- Since it is raising suspicions more, it is better to disable the extension.

## How malicious extensions harm users?

- They can get access to browsing history, cookies, and form data can lead to data theft.
- Some can monitor keystrokes or clipboard contents.
- They can steal session tokens/cookies to impersonate users on websites.
- Inject or replace ads on websites with their own, generating illicit revenue.
- Use the victim’s CPU/GPU power for cryptocurrency mining (cryptojacking), leading to performance issues and battery drain.
- Some extensions communicate with a remote server, receiving new malicious instructions.

##  How to Protect Against Malicious Extensions?

- Only install from trusted sources.
- Check permissions and give access to only that are highly necessary.
- Use browser profiles to separate personal and work.
- Keep browsers updated.

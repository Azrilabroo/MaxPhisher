
# MaxPhisher Updated by Azrilabroo

This updated version of MaxPhisher ensures seamless operation across various platforms, including Termux, Kali Linux, Windows Command Prompt, and Google Cloud Shell. Key improvements include:

1. **Runtime Error Fixes:** Continuous, error-free operation using Cloudflare for attacks.
2. **Enhanced Google OTP Phishing Pages:** Input fields are mandatory to prevent login attempts with empty fields.

---

## Setup Guidance for Any Machine

### MaxPhisher Installation and Setup in Google Cloud Shell

#### Step 1: Access Google Cloud Shell
Start an interactive session in Google Cloud Shell by running the following command:
```bash
gcloud alpha cloud-shell ssh
```

#### Step 2: Clone the MaxPhisher Repository
Clone the updated MaxPhisher repository:
```bash
git clone https://github.com/Azrilabroo/maxphisher_Updated
```

Navigate to the cloned directory:
```bash
cd Updated_BY_@Azrilabroo_Telegram
```
Then, move into the MaxPhisher directory:
```bash
cd MaxPhisher
```

#### Step 3: Install MaxPhisher
Install MaxPhisher using pip3:
```bash
pip3 install maxphisher
```

#### Step 4: Grant Execution Permissions
Navigate to the root directory and make the MaxPhisher script executable. Replace `put_your_gcloud_name` with your specific Google Cloud username:
```bash
chmod +x /home/put_your_gcloud_name/.local/bin/maxphisher
```

Verify the file permissions to ensure the script is executable:
```bash
ls -l /home/put_your_gcloud_name/.local/bin/maxphisher
```
Expected output:
```plaintext
-rwxr-xr-x 1 put_your_gcloud_name put_your_gcloud_name 209 Oct  6 10:07 /home/put_your_gcloud_name/.local/bin/maxphisher
```

#### Step 5: Add MaxPhisher to the PATH
Add the directory containing the MaxPhisher script to your system's PATH variable:

1. Open the `~/.bashrc` file in a text editor:
   ```bash
   nano ~/.bashrc
   ```

2. Add the following line at the end of the file:
   ```bash
   export PATH="$PATH:/home/put_your_gcloud_name/.local/bin"
   ```

3. Save the file (Ctrl+O, then Enter) and exit (Ctrl+X).

Reload the updated `~/.bashrc` file:
```bash
source ~/.bashrc
```

#### Step 6: Run MaxPhisher
You can now run MaxPhisher from anywhere in your Cloud Shell:
```bash
maxphisher
```

---

### Troubleshooting
- If you encounter a "command not found" error, check the installation path of MaxPhisher and ensure it matches the PATH variable in `~/.bashrc`.
- Verify that Python and pip3 are installed correctly by checking their versions:
  ```bash
  python3 --version
  pip3 --version
  ```

---

### Cross-Platform Usage
Follow the same method to install and use MaxPhisher on:
- **Windows CMD**
- **Google Cloud Shell**
- **Kali Linux**
- **Termux**

This update has been tested on all these platforms and works continuously without errors.

---

### Support
If you face any errors, issues, or need modifications, contact **@Azrilabroo** on Telegram. I’ll assist you as long as I’m alive! 🙌👀

---

### Disclaimer
This tool should only be used for educational purposes and with proper authorization.

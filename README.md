# WebVulnScanner



## What’s This?

This Perl script helps you find common web vulnerabilities in HTML files. It checks for missing security headers, potential XSS issues, open redirects, insecure form submissions, and signs of SQL injection.

## What It Does

- **Checks for Missing Security Headers:** It looks for essential headers like `Content-Security-Policy`, `X-Frame-Options`, `X-Content-Type-Options`, and `Strict-Transport-Security`.
- **Looks for XSS Vulnerabilities:** It finds inline `<script>` tags and unencoded user input that might be vulnerable.
- **Detects Open Redirects:** It checks if any `<a>` tags are using unvalidated redirects.
- **Finds Insecure Forms:** It searches for forms that send data over insecure HTTP.
- **Scans for SQL Injection:** It looks for patterns that might suggest SQL injection vulnerabilities.

## How to Use It

1. **Save the Script:** Download or clone the repository and save the `WebVulnerabilityScanner.pl` script to your computer.
2. **Get Your HTML File Ready:** Make sure the HTML file you want to scan is in the same folder as the script.
3. **Run the Script:** Open your command line and run the script like this:

   ```sh
   perl WebVulnerabilityScanner.pl your_file.html
   ```

   Just replace `your_file.html` with the name of your HTML file.

## What You’ll See

The script will let you know if it finds any issues and will give you a summary of what it found at the end.


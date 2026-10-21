# php2shell

This repo holds Nuclei templates for PHP runtime discovery. The checks are info-level only: they look for PHP version headers, session cookies, and exposed diagnostic pages. They do not exploit anything.

## Example

Run the template against a target URL:

```bash
nuclei -t php-runtime-discovery-v2.yaml -u https://example.com
```

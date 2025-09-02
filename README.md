# Deptron Nginx Config

This repository contains the Nginx configuration files used for the Deptron project.

## Files

- **nginx.conf**  
  Final HTTPS reverse proxy configuration.  
  Serves traffic for:

  - deptronrobotics.com
  - <www.deptronrobotics.com>
  - deptron.com.tr
  - <www.deptron.com.tr>

- **nginx.http-only.conf**  
  Minimal HTTP-only configuration used during the initial SSL certificate request.

## Usage

Clone this repo alongside `deptron-compose`:

```bash
git clone https://github.com/you/deptron-nginx.git
```

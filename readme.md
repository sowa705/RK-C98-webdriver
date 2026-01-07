# RK C98 Web driver offline version

This repository contains the web driver for the RK C98 keyboard downloaded from the official website.

## Running the Driver

To make the driver work you will need to serve the files using a web server. easy way is to use python's built-in HTTP server.

```bash
python3 -m http.server
```

Then open your web browser and navigate to `http://localhost:8000` to access the driver interface.

## Notes

- This is an offline version of the RK C98 web driver.
- Firefox is not supported due to lack of WebUSB support.
- Running the `index.html` file directly in a browser will not work.
- `down/` directory contains a copy of the 1.0.1 firmware
- Other RK keyboards *might* work but I don't have the images downloaded here - if it works at all it will be partially broken due to missing images.
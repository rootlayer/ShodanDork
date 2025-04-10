# ShodanDork
SHODAN DORKS 🎯 IP CAMERAS | IoT | RTSP | HTTP TITLES


🔍 "IP Camera" has_screenshot:true http
# Finds IP cameras with accessible HTTP interfaces and available screenshots.

🎯 port:554 has_screenshot:true
# Devices with RTSP port open and screenshots available – often IP cameras.

📡 "ONVIF" port:8080
# Devices using the ONVIF protocol (commonly IP cameras) on port 8080.

📷 "Hikvision" port:8000
# Hikvision cameras or systems running on their default port.

🌍 port:554 "RTSP" has_screenshot:true country:ir
# RTSP-enabled devices in Iran with visible screenshots.

🧩 "Server: uc-httpd" has_screenshot:true country:ir
# Devices in Iran using the lightweight uc-httpd server – common in embedded/IoT systems.

🧱 "Server: Boa" has_screenshot:true
# Systems using Boa web server – often outdated and found in legacy IoT devices.

🖥️ http.title:"IP Camera Viewer" has_screenshot:true
# Web interfaces with "IP Camera Viewer" in their title – likely camera dashboards.

🎥 http.title:"webcamXP" has_screenshot:true
# Devices running the webcamXP streaming software, usually IP cams.

🧪 Web Version="3.1.3.150324" http.favicon.hash:999357577
# Finds devices with a specific software version via favicon hash.

# Bar-code-and-QR-code-Scan
We use this code to scan QR code and Bar code We have imported the pyzbar ,cv2 and numpy libraries. We have then used the VideoCaptur() to open the camera. The get_qr_dat() function to detect the QR code in the image, then used the Decode() function and printed the value for the users. The draw_polygon() function ,we used polylines() function To draw a polygon around the edges of the bar core and QR code , and used putText() function to write and show text of What information the bar code and QR code contain . As a result, the Decode function returns the content of the QR code, coordinates of the corners of the box, and binarized QR code.

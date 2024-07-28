# Project info

Image encrypter:

It can be used  to encrypt message to the images and can be send with end to end encryption.

Every image is collection of multiple pixels. Each of these pixels is defined by a 24 bit RGB value, 8 for each R,B & G. 
If LSB of this value is modified, then change is so minimal that it is undetectable to human eyes. I took advantage of it by replacing LSB bit to a message bit. This is called as image steganography.

## Installation

1. Clone the repository:

```
git clone https://github.com/thehardiik/Trojan-Pixel.git
```

2. Navigate to the project directory:

```
cd Trojan-Pixel
```

3. Navigate to the server directory

```
cd backend-server
```

4. Install Dependencies

```
npm install
```

5. Start the server:

```
npm run start
```

6. Opne new terminal and navigate to Trojan-Pixel:

```
cd Trojan-Pixel
```

7. Navigate to the client directory

```
cd client
```

8. Install Dependencies

```
npm install
```

9. Start the client:

```
npm run dev
```

10. Access the application in your browser 


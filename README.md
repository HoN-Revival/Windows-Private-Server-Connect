# Windows-Private-Server-Connect
A simple guide on how to edit the HoN shortcut to point at private servers

## How to connect to custom servers?

On Windows (for both 32 and 64-bit clients) it's quite easy.

1. Simply make a shortcut to your `hon.exe` or `hon_64.exe`.

    ![HoN shortcut image](https://i.imgur.com/nfSsGah.png)
    
2. Right-click the shortcut and go to `Properties`.

3. In the `Target` field, scroll to the end and add a space after the last quotation mark.

    ![Highlighted 'Target' section](https://i.imgur.com/IivxRdW.png)
    
    ![Illustration of placing a space after the ending quotation mark](https://i.imgur.com/LN2aka7.png)
    
4. Add the following arguments to the executable, pointed to your custom server.

    `-masterserver <address> -webserver <address> -messageserver <address>`
    
    Where the `<address>` is in the form of `<IP>:<port>` or `<IP>` or `<URL>` or `<URL>:<port>`.
    
    The default port (if unspecified) is the default HTTP port of `80`.
    
    The final target field should look something like this:
    
    ```
    "C:\Program Files\Heroes of Newerth x64\hon_x64.exe" -masterserver <IP>:<port> -webserver <IP>:<port> -messageserver <IP>:<port>
    ```
    
## Connecting to Project Kongor

1. Follow the above steps 1-3.
    
2. Add the following arguments
    TODO
    
    The final target field should look like this:
    TODO
    


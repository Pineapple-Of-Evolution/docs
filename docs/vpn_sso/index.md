# VPN/SSO configuration

## Onboarding new user
1. Login to [defguard](https://vpn.pineapple.pp.ua/) as admin
2. Navigate to users tab ![users tab](./images/users.png)
3. Click "Add new" ![add new](./images/add_new.png)
4. Fill all needed fields ![user](./images/user.png), use @pineapple.pp.ua as subdomain for email
5. Provide login/password to user

## Wireguard install on Windows
1. Install wireguard from [https://download.wireguard.com/windows-client/](https://download.wireguard.com/windows-client/)
2. Configure client using [Configuring Wireguard client](#configuring-wireguard-client)

## Wireguard install on macOS
1. Install wireguard from [AppStore](https://apps.apple.com/ru/app/wireguard/id1451685025?mt=12)
2. Configure client using [Configuring Wireguard client](#configuring-wireguard-client)

## Configuring Wireguard client 
1. Login to [defguard](https://vpn.pineapple.pp.ua/) with your credentials
2. Tap add new device ![new device](./images/new_device.png)
3. Choose name for your device and pick "Generate key pair" option. Each device must have its own config! ![add device](./images/add_device.png)
4. Save configuration to file ![config](./images/config.png)
5. Import it in wireguard (example for macOS) ![example](./images/example.png)
6. Activate new connection and check if you can access any private resource


## Password change
1. Login to [defguard](https://vpn.pineapple.pp.ua/) with your credentials
2. Tap "Edit profile" ![edit profile](./images/edit_profile.png)
3. Tap "Change password" ![change password](./images/change_password.png)
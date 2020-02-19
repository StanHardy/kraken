# kraken-client
<img width="200" src="https://github.com/arcaneiceman/kraken-client/blob/master/src/assets/kraken-logo.png"/>

## Kraken: A multi-platform distributed brute-force password cracking system

Click <a href="https://kraken.work/help">here</a> for a guide to Kraken

### Change Log:

#### 1.0.5
Updates:
- These alerts that you are seeing now
- Added a note about multi-core (browser) / choosing devices (local)
- FAQ section in help
- Local Client enables dev console

Fixed Bug:
- Change Password UI Fix
- Forget Password does not immediatly bump you to login
- If you delete remote worker, it shuts off now
- Request Name can be 40 characters now

#### 1.0.4
Fixed Bug:
- Bad event bus library needed cleanup code

#### 1.0.3
Updates:
- Electron app is now resizable
Fixed Bugs:
- Emails with symbols are now URL encoded
- Electron App dead links fixed
- Updates between various windows are now fast
- Closing Electron App while worker is running will give a prompt
- Transtion away from dashboard while worker is running will give a prompt

#### 1.0.2
Fixed Bugs:
- Auto logout after token expired
- Active core count not setting properly



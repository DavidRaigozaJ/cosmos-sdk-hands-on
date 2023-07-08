# cosmos-sdk-hands-on

Here we make a hands-on excersice to understand how cosmos-sdk works.

## what we learnt

<li>
  install ignite CLI
  </li>
<li>
  scaffold a basic blockchain
    </li>
<li>
  interact via CLI
<li>
  boot the frontend in localhost
  </li>
<li>
  send a message
</li>

## QuickStart
```
git clone https://github.com/DavidRaigozaJ/cosmos-sdk-hands-on
cd cosmos-sdk-hands-on
cd checkers
ignite chain serve
```

interact with another chain in a new terminal

```
checkersd status
```
run the GUI (graphic user interface)

```
cd vue
npm install
npm run dev
```

use Keplr wallet to connect to the dapp 

## Send your first message

```
ignite scaffold message createPost title body
```

# MICRO-FRONTEND

This application is built with micro frontend approach in which a front-end app is decomposed into individual “microapps” working loosely together.  
In order to understand clearly the application, you should take a look the workshop slide [here](https://docs.google.com/presentation/d/15Hme2vXkNrUYNverqiYGxAr4MhozlDGTDNKyxdwOc_s/edit?usp=sharing)

## Features
Bill Gates is one of billionaires in the world. He's very rich. He has a lot of money.  
For that reason, today we will together help him spent his money on our application which following details:

1. Display Bill remaining money amount after buy / sell some products.
2. Display a list of products, each product should have buy / sell action.
3. Show and update the receipt on every buy / sell action.
4. Enable / disable buy button of any product which has unit price > remaining money amount.

![image](documentation/spend_bill_gate_money.png)
Inspired by https://neal.fun/spend/  

## Demos
* Fragment wallet (Team 1): [--> View team 1 sandbox](https://aavn-ct-workshop.github.io/micro-frontend-team-one/sandbox.html)
* Fragment product item (Team 2): [--> View team 2 sandbox](https://aavn-ct-workshop.github.io/micro-frontend-team-two/sandbox.html)
* Fragment receipt (Team 3): [--> View team 3 sandbox](https://aavn-ct-workshop.github.io/micro-frontend-team-three/sandbox.html)
* Integrated application: [--> View integrated app](https://aavn-ct-workshop.github.io/micro-frontend/application/index.html)

## How to run app in local
To run the integrated app in local,  
you must have 3 additional repositories need to check out: `micro-frontend-team-one`, `micro-frontend-team-two` and `micro-frontend-team-three`.  
Then simply run `docker-compose up --build`

## Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/dieuph"><img src="https://avatars3.githubusercontent.com/u/9255073?v=4" width="70px;" alt=""/><br /><sub><b>Dieu Pham</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/tai-tran-tan"><img src="https://avatars3.githubusercontent.com/u/44283461?v=4" width="70px;" alt=""/><br /><sub><b>Tai Tran</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/tshen-dev"><img src="https://avatars2.githubusercontent.com/u/22613270?v=4" width="70px;" alt=""/><br /><sub><b>Hen Tran</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/nmanhhung1707"><img src="https://avatars1.githubusercontent.com/u/26823475?v=4" width="70px;" alt=""/><br /><sub><b>Hung Nguyen</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/pnqphong"><img src="https://avatars3.githubusercontent.com/u/22651438?v=4" width="70px;" alt=""/><br /><sub><b>Phong Pham</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/hgky95"><img src="https://avatars3.githubusercontent.com/u/33622784?v=4" width="70px;" alt=""/><br /><sub><b>Ky Huynh</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/fluwins"><img src="https://avatars3.githubusercontent.com/u/50920010?v=4" width="70px;" alt=""/><br /><sub><b>Tai Tran Thien</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/bkimtho"><img src="https://avatars2.githubusercontent.com/u/51102860?v=4" width="70px;" alt=""/><br /><sub><b>Tho Bui</b></sub></a><br /></td>
  </tr>
</table>

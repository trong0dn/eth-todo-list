# Ethereum Blockchain DApp - To-do List

*Warning:* Smart contracts are notorious for security vulnerabilities detected, here are some for this program.
| Description | Weaknesses  |   CVE ID    |   GHSA ID   |
| ----------- | ----------- | ----------- | ----------- |
| cookiejar Regular Expression Denial of Service via Cookie.parse function | [CWE-1333](https://cwe.mitre.org/data/definitions/1333.html) | [CVE-2022-25901](https://nvd.nist.gov/vuln/detail/CVE-2022-25901) | [GHSA-h452-7996-h45h](https://github.com/advisories/GHSA-h452-7996-h45h) |
| ReDoS Vulnerability in ua-parser-js version | [CWE-400](https://cwe.mitre.org/data/definitions/400.html) <br/> [CWE-1333](https://cwe.mitre.org/data/definitions/1333.html) | [CVE-2022-25927](https://nvd.nist.gov/vuln/detail/CVE-2022-25927) | [GHSA-fhg7-m89q-25r3](https://github.com/advisories/GHSA-fhg7-m89q-25r3) |
| http-cache-semantics vulnerable to Regular Expression Denial of Service| [CWE-1333](https://cwe.mitre.org/data/definitions/1333.html)  | [CVE-2022-25881](https://nvd.nist.gov/vuln/detail/CVE-2022-25881) | [GHSA-rc47-6667-2j5j](https://github.com/advisories/GHSA-rc47-6667-2j5j) |
| semver vulnerable to Regular Expression Denial of Service | [CWE-1333](https://cwe.mitre.org/data/definitions/1333.html) | [CVE-2022-25883](https://nvd.nist.gov/vuln/detail/CVE-2022-25883) | [GHSA-c2qf-rxjj-qqgw](https://github.com/advisories/GHSA-c2qf-rxjj-qqgw) |
| Server-Side Request Forgery in Request | [CWE-918](https://cwe.mitre.org/data/definitions/918.html) | [CVE-2023-28155](https://nvd.nist.gov/vuln/detail/CVE-2023-28155) | [GHSA-p8p7-x288-28g6](https://github.com/advisories/GHSA-p8p7-x288-28g6) |
| tough-cookie Prototype Pollution vulnerability | [CWE-1321](https://cwe.mitre.org/data/definitions/1321.html) | [CVE-2023-26136](https://nvd.nist.gov/vuln/detail/CVE-2023-26136) | [GHSA-72xf-g2v4-qvf3](https://github.com/advisories/GHSA-72xf-g2v4-qvf3) |
| Insufficient validation when decoding a Socket.IO packet | [CWE-20](https://cwe.mitre.org/data/definitions/20.html) <br/> [CWE-754](https://cwe.mitre.org/data/definitions/754.html) | [CVE-2023-32695](https://nvd.nist.gov/vuln/detail/CVE-2023-32695) | [GHSA-cqmj-92xf-r6r9](https://github.com/advisories/GHSA-cqmj-92xf-r6r9) |
| Prototype Pollution in minimist | [CWE-1321](https://cwe.mitre.org/data/definitions/1321.html) | [CVE-2021-44906](https://nvd.nist.gov/vuln/detail/CVE-2021-44906) | [GHSA-xvch-5gv4-984h](https://github.com/advisories/GHSA-xvch-5gv4-984h) |

## Description

A simple to-do list powered by Ethereum smart contracts to understand how blockchain works and its application on decentralized platforms. Unlike traditional to-do list applications, there is no centralized database where data is stored and retrieved. The data content, script (in this case, the smart contracts), and list items are stored directly on a network distributed over the blockchain nodes.

## Working Technology Stack
<p align="left"> 
  <a href="https://docs.soliditylang.org/en/v0.5.3/" target="_blank"> <img src="https://docs.soliditylang.org/en/v0.5.3/_images/logo.svg" alt="solidity" width="40" height="40"/> </a> 
  <a href="https://www.trufflesuite.com/truffle" target="_blank"> <img src="https://trufflesuite.com/img/truffle-logo-light.svg" alt="truffle" width="40" height="40"/> </a> 
  <a href="https://www.trufflesuite.com/ganache" target="_blank"> <img src="https://seeklogo.com/images/G/ganache-logo-9BC4FC62A4-seeklogo.com.png" alt="ganache" width="40" height="40"/> </a> 
  <a href="https://metamask.io/" target="_blank"> <img src="https://raw.githubusercontent.com/MetaMask/brand-resources/master/SVG/metamask-fox.svg" alt="metamask" width="40" height="40"/> </a> 
  <a href="https://web3js.readthedocs.io/en/v1.3.4/" target="_blank"> <img src="https://raw.githubusercontent.com/ChainSafe/web3.js/1.x/assets/logo/web3js.jpg" alt="web3js" width="40" height="40"/> </a> 
  <a href="https://mochajs.org/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/mochajs/mochajs-icon.svg" alt="mocha" width="40" height="40"/> </a> 
  <a href="https://www.chaijs.com/" target="_blank"> <img src="https://gist.githubusercontent.com/keithamus/3d8cfbaeddf8bdf5f7cd94a3bdae0934/raw/63ca295f3aa7e1b94b598d84dfe0330383497a8c/Chai%2520Logo.svg" alt="chai" width="40" height="40"/> </a> 
  <a href="https://nodejs.org/en/" target="_blank"> <img src="https://nodejs.org/static/images/logo.svg" alt="node" width="40" height="40"/> </a> 
</p>

## Dependencies
* [Solidity](https://docs.soliditylang.org/en/v0.8.11/) v5.0.0 - High-level language for implementing Smart Contracts 
* [Truffle Suite Framework](https://www.trufflesuite.com/truffle) v5.0.2 - Ethereum Decentralized Application Framework 
* [Ganache](https://www.trufflesuite.com/ganache) v2.5.4 - Personal Ethereum blockchain run on a local machine
* [Metamask](https://metamask.io/) v10.8.2 - Ethereum Wallet Google Chrome extension 
* [web3.js](https://web3js.readthedocs.io/en/v1.3.4/) v1.3.4 - Library for interacting with Ethereum JavaScript API for blockchain (depreciated)
* [Mocha](https://mochajs.org/) v9.1.3 - JavaScript testing framework running on Node.js
* [Chai](https://www.chaijs.com/) v4.1.2 - BDD / TDD assertion library for Node.js
* [Node.js](https://nodejs.org/en/) v16.13.1 - JavaScript runtime engine

## Deployment 
```bash
# Clone 
$ https://github.com/trong0dn/eth-todo-list.git

# Install dependencies 
$ npm install
$ npm install -g truffle@5.0.2

# Migrate 
$ truffle migrate -reset

# Run the app
$ npm install lite-server@2.3 --save-dev
$ npm run dev
```

### Listing Tasks
A task is modeled using a struct with a state variable to map tasks to a task counter.

```solidity
// TodoList.sol
pragma solidity >=0.4.22 <0.9.0;

contract TodoList {
  uint public taskCount = 0;

  struct Task {
    uint id;
    string content;
    bool completed;
  }

  mapping(uint => Task) public tasks;
}
```

### Creating Tasks 

The function createTask passes a string argument for the name of the task which is store directly on the blockchain. This event is triggered when a new task is created via the client-side interaction. Solidity performs these actions via event-based listening. 

```solidity
// TodoList.sol
pragma solidity >=0.4.22 <0.9.0;

contract TodoList {

  // ...

  event TaskCreated(
    uint id,
    string content,
    bool completed
  );

  // ...

  function createTask(string memory _content) public {
    taskCount++;
    tasks[taskCount] = Task(taskCount, _content, false);
    emit TaskCreated(taskCount, _content, false);
  }
}
```

![new_task](https://user-images.githubusercontent.com/55768917/148163029-020e830f-8677-4c2b-84f7-d1f9b5e2fa52.gif)

### Completing Tasks

Selecting the checkbox for tasks on the todo list to be completed will invoke an update upon the smart contract. 

```solidity
// TodoList.sol
pragma solidity >=0.4.22 <0.9.0;

contract TodoList {

  // ...

  event TaskCompleted(
    uint id,
    bool completed
  );

  // ...

  function toggleCompleted(uint _id) public {
    Task memory _task = tasks[_id];
    _task.completed = !_task.completed;
    tasks[_id] = _task;
    emit TaskCompleted(_id, _task.completed);
  }
}
```

![complete_task](https://user-images.githubusercontent.com/55768917/148163040-9a482d01-64f9-43ae-bec3-b7e77fa5ead1.gif)

### Testing
```bash
# Run Test 
$ truffle test 
```

```javascript
// TodoList.test.js
it ('toggles tasks completion', async () => {
  const result = await this.todoList.toggleCompleted(1)
  const task = await this.todoList.tasks(1)
  assert.equal(task.completed, true)
  const event = result.logs[0].args 
  assert.equal(event.id.toNumber(), 1)
  assert.equal(event.completed, true )
})
```

![testing](https://user-images.githubusercontent.com/55768917/148163313-1c9c2e49-590a-45b7-9488-69ad739b0a9a.png)

## Ganache Personal Blockchain 
A personal Ethereum blockchain that you can use to run tests, execute commands, and inspect state while controlling how the chain operates using the truffle suite. Each addition and completion of a tasks results in a transaction to the smart contract.

![Screenshot 2022-01-04 235850](https://user-images.githubusercontent.com/55768917/148163360-cc8cea95-9cab-4b27-90e3-845c22cd6054.png)

## Metamask

A Google Chrome extension allowing blockchain applications to be performed housing a crypto-wallet. Metamask allows for managing our personal account when connecting to the blockchain, as well as manage ETH funds needed to pay for transactions. 

![Metamask](https://user-images.githubusercontent.com/55768917/148163515-c72ddadd-bf4c-473f-adc9-2280882a0cae.png)

## Acknowledgement

Original idea: https://github.com/dappuniversity/eth-todo-list <br>
Fixes for depreciated Web3.js and Bootstrap bump: https://github.com/smrnjeet222/eth-todo-list-blockchain <br>
README file ideas: https://github.com/kenneth-liang/Ethereum-Todo-List <br>

## Disclaimer

Copyright disclaimer under section 107 of the Copyright Act 1976, 
allowance is made for “fair use” for purposes such as criticism, 
comment, news reporting, teaching, scholarship, education, and research.

Fair use is a use permitted by copyright statute that might otherwise 
be infringing.

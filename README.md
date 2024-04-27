// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.7;

contract helloWorld {
 string public text = "Hello World!";

 function callHelloWorld() public view returns (string memory) {
   return text;
 }
}

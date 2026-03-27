# TodoList.sol
Deploy a contract on Base
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract TodoList {
    string[] public todos;

    function addTodo(string memory _todo) public {
        todos.push(_todo);
    }
}

# 30-days-solidity-challenge

// SPDX-License-Identifier: MIT

pragma solidity ^0.8.19;

contract clickcountter{

    uint public clickcounter;

    function clickup () public {
        clickcounter++;
    }
    function clickdown () public {
        clickcounter = clickcounter  -1;
    }
}

# Uniswap Spot vs TWAP Price

After listening to the Uniswap V3 Oracle Workshop by Alice Henshaw, I was interested by the concept of the Uniswap V3 pools having a built in oracle. What stood out to me the most was the concept of using a time weighted average price instead of a spot price to help web3 protocols mitigate price manipulation attacks. 

Using the TWAP, over a longer time period should smooth out these spikes of activity (for example: larger purchases or large flashloan swaps). 

This also introduces a new balancing act, to find those goldilocks conditions between having fresh prices and avoiding manipulation. I suppose the it will vary on each user's needs.

## UniCode 2021 Project

The goal is to learn how to derive the spot price and the TWAP to better understand how to integrate this into other things and to get familiar with interacting with the Uniswap contracts.
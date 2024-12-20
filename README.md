# Unhandled Promise Rejection in `getBalance` Function

This repository demonstrates a common error in DApps:  failure to handle promise rejections in asynchronous functions. The `getBalance` function attempts to retrieve an Ether balance using web3.js, but lacks error handling.  This can lead to the application silently failing or producing unexpected results.

The solution provides an improved version with a `try...catch` block to gracefully handle errors and prevent application crashes.
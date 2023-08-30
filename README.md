
# ZK Circuit Implementation: ZK SNARK Designer for Polygon 🛠

## Challenge

The challenge is to design a zkSNARK circuit using the circom programming language to implement specific logical gates. The primary aim is to prove that you know the inputs \( A = 0 \) and \( B = 1 \) that yield an output of 0.

## Project Deep Dive

This project involves creating a custom circuit, deploying it to a testnet, finding a public RPC, and using environmental variables to secure sensitive data. For a detailed walkthrough, refer to the instructional video provided.

## Tools Used

- Hardhat-circom template for circuit design, compilation, and proof generation.

## Project Rubric

To successfully complete this project, you should:

1. Write a correct `circuit.circom` implementation.
2. Compile the circuit to generate circuit intermediaries.
3. Generate a proof using inputs \( A=0 \) and \( B=1 \).
4. Deploy a Solidity verifier to Sepolia or Mumbai Testnet.
5. Call the `verifyProof()` method on the verifier contract and assert the output is true.

## Submission Requirements

1. Add your project to GitHub with a public link.
2. Include this README.md in the project root.
3. Record a 5-min or less video walkthrough (Link to be added).
4. Demo your code in a test environment in the video.

## Video Walkthrough

[Watch the video walkthrough here](#) (Link to be added)

In the video, I will cover:
- How to build a circum circuit using the JK ZK Snark module.
- Explanation of logical operations using pragma circum 2.0.
- Deployment of the circuit on polygonscan.com.

## License

MIT License

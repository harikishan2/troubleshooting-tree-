# TreeWise — Technical Troubleshooting Decision Support System

A polished DSA working model demonstrating a binary decision tree and four traversal algorithms.

## Features
- Seven-node troubleshooting decision tree with a node legend
- Preorder, inorder, postorder and level-order traversal sequences
- Step-by-step node highlighting and Play/Pause traversal animation
- Interactive Yes/No troubleshooting simulator
- Light/dark theme toggle and print option
- Python 3 implementation, expected output and complexity table
- Viva questions and presentation tips

## Run locally
Open `index.html` in a modern browser. No server or external libraries are required. Run the Python example separately with Python 3 if you want to verify the console output.

## Publish using GitHub Pages
1. Create a public repository such as `dsa-troubleshooting-tree`.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose branch `main` and folder `/(root)`, then click **Save**.
5. Wait for GitHub Pages to display the live website URL.

## Node guide
- A: Does the device power on?
- B: Check the power cable.
- C: Check the internet connection.
- D: Connect the power cable.
- E: Test the power outlet.
- F: Restart the router.
- G: Check internet service status.

This is an educational prototype using a fixed tree, not a production diagnostic engine.

## Traversal sequences
- Preorder: `A B D E C F G`
- Inorder: `D B E A F C G`
- Postorder: `D E B F G C A`
- Level-order: `A B C D E F G`

## Complexity
- Time for all four traversals: **O(n)**
- Recursive traversal auxiliary space: **O(h)**
- Level-order auxiliary space: **O(w)**

Here, `n` = number of nodes, `h` = tree height, and `w` = maximum width.

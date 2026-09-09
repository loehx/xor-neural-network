# XOR Neural Network

An interactive visualization of a small neural network that learns the XOR function. Click input neurons to toggle values, adjust weights and biases, and watch activations propagate through the network in real time.

**Live demo:** [https://loehx.github.io/xor-neural-network/](https://loehx.github.io/xor-neural-network/)

## Features

- Visual feed-forward network with input, hidden, and output layers
- Click input neurons to set 0 or 1
- Click synapse weights and neuron biases to edit them
- Preconfigured XOR weights loaded on startup
- State persisted in the browser via `localStorage`

## Run locally

Open `index.html` in a web browser, or serve the project with any static file server:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## License

MIT © [Alexander Löhn](https://loehx.com/)

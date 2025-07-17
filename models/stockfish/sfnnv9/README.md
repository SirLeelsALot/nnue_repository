# Stockfish, SFNNv9

## Big network architecture (`Stockfish::Eval::NNUE::NetworkBig`)

Network size: 3072->16->32->1

File format: big_net.txt

## Small network architecture (`Stockfish::Eval::NNUE::NetworkSmall`)

Network size: 128->16->32->1

File format: small_net.txt

# Training data 
- from [commit](https://github.com/official-stockfish/Stockfish/commit/0716b845fdef8a20102b07eaec074b8da8162523): https://robotmoon.com/nnue-training-data
- from [PR](https://github.com/official-stockfish/Stockfish/pull/4915)

# Training code
- [nnue/pytorch](https://github.com/official-stockfish/nnue-pytorch)

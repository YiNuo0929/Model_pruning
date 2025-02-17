
## Implement algorithm performed in Network Slimming.
• Architecture: VGG

• Dataset: CIFAR10
1. Complete scaling factor distribution visualization
2. Complete different prune ratio 
  a. Prune ratio 0.5 (5%)
  b. Prune ratio 0.9 (10%)
3. Run sparsity_train.ipynb for sparsity regularization training
4. Run vggprune.ipynb for model pruning
5. Run train_prune_model.ipynb to train pruned model (fine-tune)
## Report 大綱
• Plot sparsity-training accuracy of origin model over epochs

• Plot scaling factor distribution with 3 different λ value

• Show model test accuracy after pruning 50% channels 

• Show model test accuracy after pruning 90% channels 

• Plot training (fine-tuning) accuracy of pruned 90% model over epochs

• Show what problem you encounter and how you solve it

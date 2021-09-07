### Arabic Denormalization ###
Arabic is a morphologically rich language which can cause data sparsity issues for many NLP models. To overcome such, many popular toolkits such as MADAMIRA and FARASA have been proposed. However, many of the settings for these systems result in destructive normalization - or lack of ability to reconstruct the original data.

This is a tool for training a simple sequence-to-sequence model where tokenized data is fed into the model and proper Arabic is generated.

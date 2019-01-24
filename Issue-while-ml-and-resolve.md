##Out of Memory when try to train
https://github.com/tensorflow/models/issues/1817

train_config: {
  batch_size: 1
  batch_queue_capacity: 150
  num_batch_queue_threads: 8
  prefetch_queue_capacity: 10
  optimizer {
    rms_prop_optimizer: {
      learning_rate: {
        exponential_decay_learning_rate {
          initial_learning_rate: 0.004
          decay_steps: 800720
          decay_factor: 0.95
        }
      }
      momentum_optimizer_value: 0.9
      decay: 0.9
      epsilon: 1.0
    }
  
  }

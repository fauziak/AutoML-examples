## Error for 1_Baseline

Found input variables with inconsistent numbers of samples: [1, 17687]
Traceback (most recent call last):
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 1087, in _fit
    trained = self.train_model(params)
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 372, in train_model
    mf.train(results_path, model_subpath)
  File "/usr/local/lib/python3.7/dist-packages/supervised/model_framework.py", line 165, in train
    train_data, validation_data = self.validation.get_split(k_fold, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validation_step.py", line 30, in get_split
    return self.validator.get_split(k, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validator_split.py", line 83, in get_split
    random_state=self.random_seed + repeat,
  File "/usr/local/lib/python3.7/dist-packages/sklearn/model_selection/_split.py", line 2417, in train_test_split
    arrays = indexable(*arrays)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 378, in indexable
    check_consistent_length(*result)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 334, in check_consistent_length
    % [int(l) for l in lengths]
ValueError: Found input variables with inconsistent numbers of samples: [1, 17687]


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 2_DecisionTree

Found input variables with inconsistent numbers of samples: [1, 17687]
Traceback (most recent call last):
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 1087, in _fit
    trained = self.train_model(params)
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 372, in train_model
    mf.train(results_path, model_subpath)
  File "/usr/local/lib/python3.7/dist-packages/supervised/model_framework.py", line 165, in train
    train_data, validation_data = self.validation.get_split(k_fold, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validation_step.py", line 30, in get_split
    return self.validator.get_split(k, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validator_split.py", line 83, in get_split
    random_state=self.random_seed + repeat,
  File "/usr/local/lib/python3.7/dist-packages/sklearn/model_selection/_split.py", line 2417, in train_test_split
    arrays = indexable(*arrays)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 378, in indexable
    check_consistent_length(*result)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 334, in check_consistent_length
    % [int(l) for l in lengths]
ValueError: Found input variables with inconsistent numbers of samples: [1, 17687]


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 1_Default_Xgboost

Found input variables with inconsistent numbers of samples: [1, 17687]
Traceback (most recent call last):
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 1087, in _fit
    trained = self.train_model(params)
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 372, in train_model
    mf.train(results_path, model_subpath)
  File "/usr/local/lib/python3.7/dist-packages/supervised/model_framework.py", line 165, in train
    train_data, validation_data = self.validation.get_split(k_fold, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validation_step.py", line 30, in get_split
    return self.validator.get_split(k, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validator_split.py", line 83, in get_split
    random_state=self.random_seed + repeat,
  File "/usr/local/lib/python3.7/dist-packages/sklearn/model_selection/_split.py", line 2417, in train_test_split
    arrays = indexable(*arrays)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 378, in indexable
    check_consistent_length(*result)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 334, in check_consistent_length
    % [int(l) for l in lengths]
ValueError: Found input variables with inconsistent numbers of samples: [1, 17687]


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 2_Default_NeuralNetwork

Found input variables with inconsistent numbers of samples: [1, 17687]
Traceback (most recent call last):
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 1087, in _fit
    trained = self.train_model(params)
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 372, in train_model
    mf.train(results_path, model_subpath)
  File "/usr/local/lib/python3.7/dist-packages/supervised/model_framework.py", line 165, in train
    train_data, validation_data = self.validation.get_split(k_fold, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validation_step.py", line 30, in get_split
    return self.validator.get_split(k, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validator_split.py", line 83, in get_split
    random_state=self.random_seed + repeat,
  File "/usr/local/lib/python3.7/dist-packages/sklearn/model_selection/_split.py", line 2417, in train_test_split
    arrays = indexable(*arrays)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 378, in indexable
    check_consistent_length(*result)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 334, in check_consistent_length
    % [int(l) for l in lengths]
ValueError: Found input variables with inconsistent numbers of samples: [1, 17687]


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 3_Default_RandomForest

Found input variables with inconsistent numbers of samples: [1, 17687]
Traceback (most recent call last):
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 1087, in _fit
    trained = self.train_model(params)
  File "/usr/local/lib/python3.7/dist-packages/supervised/base_automl.py", line 372, in train_model
    mf.train(results_path, model_subpath)
  File "/usr/local/lib/python3.7/dist-packages/supervised/model_framework.py", line 165, in train
    train_data, validation_data = self.validation.get_split(k_fold, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validation_step.py", line 30, in get_split
    return self.validator.get_split(k, repeat)
  File "/usr/local/lib/python3.7/dist-packages/supervised/validation/validator_split.py", line 83, in get_split
    random_state=self.random_seed + repeat,
  File "/usr/local/lib/python3.7/dist-packages/sklearn/model_selection/_split.py", line 2417, in train_test_split
    arrays = indexable(*arrays)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 378, in indexable
    check_consistent_length(*result)
  File "/usr/local/lib/python3.7/dist-packages/sklearn/utils/validation.py", line 334, in check_consistent_length
    % [int(l) for l in lengths]
ValueError: Found input variables with inconsistent numbers of samples: [1, 17687]


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new


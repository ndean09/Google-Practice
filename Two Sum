class Solution(Object):
  def twoSum(self, nums, target):
  hash_map = {}
  for idx, value in enumerate(nums):
    hash_map[value]=idx
  for idx1, value in enumerate(nums):
    if target-value in hash_map:
      idx2 = hash_map[target-value]
      if idx1 != idx2:
        return [idx1+1, idx2+1]
    

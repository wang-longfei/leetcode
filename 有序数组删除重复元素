class Solution(object):
    def removeDuplicates(self, nums):
        """
        :type nums: List[int]
        :rtype: int
        """
        number=0
        if len(nums)==0:
            return 0
        else:
            for i in range(len(nums)):
                if nums[number]!=nums[i] :
                    number=number+1
                    nums[number]=nums[i]
            return (number+1)

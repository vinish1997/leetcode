# Next Greater Element I

## Problem Description

You are given two integer arrays `nums1` and `nums2` where `nums1` is a subset of `nums2`. Find the **next greater element** for each element of `nums1` in the order of their appearance in `nums1`.

The **next greater element** of some element `x` in `nums2` is the first greater element that is to the right of `x` in `nums2`. If there is no next greater element, the answer for this element is `-1`.

### Constraints
- `1 <= nums1.length <= nums2.length <= 1000`
- `0 <= nums1[i], nums2[i] <= 10<sup>4</sup>`
- All elements in `nums1` and `nums2` are unique.
- All elements of `nums1` are also in `nums2`.

---

## Examples

### Example 1

**Input:**

```
nums1 = [4,1,2]
nums2 = [1,3,4,2]
```

**Output:**

```
[-1, 3, -1]
```

**Explanation:**
The next greater element for each value of `nums1` is as follows:

- 4 is in `nums2 = [1,3,4,2]`. There is no next greater element, so the answer is -1.
- 1 is in `nums2 = [1,3,4,2]`. The next greater element is 3.
- 2 is in `nums2 = [1,3,4,2]`. There is no next greater element, so the answer is -1.

### Example 2

**Input:**

```
nums1 = [2,4]
nums2 = [1,2,3,4]
```

**Output:**

```
[3, -1]
```

**Explanation:**
The next greater element for each value of `nums1` is as follows:

- 2 is in `nums2 = [1,2,3,4]`. The next greater element is 3.
- 4 is in `nums2 = [1,2,3,4]`. There is no next greater element.

# # Iterative-Closest-Point-ICP-

## Overview
Iterative Closest Point (ICP) is an algorithm used to align two sets of points by estimating the transformation (rotation and translation) between them. It iteratively refines the alignment by minimizing the distance between corresponding points in the two sets.

## Code Explanation
* ``` bash
  icp_matching(previous_points, current_points)
  ```
  The icp_matching function takes two sets of points (previous and current frames) as input and returns the estimated rotation matrix R and  translation vector T that aligns the current points to the previous points.

</table>

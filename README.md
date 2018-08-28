# fin1

In this project we aimed to solve the issue of our pi aproximation being wildly off. The reason for the catostrophic precision loss was due to repeated multiplication of small floating point numbers, which in turn lead to very large floating point errors. The solution to this problem was to flip the number over, so instead of using very small numbers, we used very large ones. After adjusting the formula to account for this, precision now continually increases as n increases.

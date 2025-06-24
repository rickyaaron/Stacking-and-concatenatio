# STACKING-AND-CONCATINATION
arrA=np.array([[1,2],[3,4]])

arrB=np.array([[5,6],[7,8]])

#vertital stacking

print("vertically stacked:\n",np.vstack((arrA,arrB)))

#horizontal stacking

print("horizontally stacked:\n",np.stack((arrA,arrB)))

O/P:

vertically stacked:

[[1 2]

[3 4]

[5 6]

[7 8]]

horizontally stacked:

[[[1 2]

[3 4]]

[[5 6]

[7 8]]]# Stacking-and-concatenatio

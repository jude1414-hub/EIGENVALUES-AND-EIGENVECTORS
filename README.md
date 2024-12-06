# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
    #Program to find the eigen values and eigen vectors.
    #Developed by: Jude Clement Jose G
    #RegisterNumber:24005310
    import numpy as np

    # Define the matrix
    A = np.array([[-2, 2, -3],
                [2, 1, -6],
                [-1, -2, 0]])

    # Calculate the eigenvalues and eigenvectors
    eigenvalues, eigenvectors = np.linalg.eig(A)

    # Print the results

    print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")


## Output:
![alt text](image.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

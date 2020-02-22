## Transposition

A = np.array([[1,2,3],[4,5,6]])

A.T

## Dot product 

A = np.array([[1,2,3],
              [4,5,6]])
              
B = np.array([[9,8],
              [7,6],
              [5,4]])
              
np.dot(A,B)

A @ B

## Matrix division

C = A @ np.linalg.inv(B)


## Linear Transformations

v = np.array([1,2])

A = np.array([[2,3],
              [5,2]])

t = A @ v

## Afine Transformations

v = np.array([1,1])

A = np.array([[5,2],
              [3,1]])
              
b = np.array([-2,-6])

t = A @ v + b

## Eigenvalues & Eigenvectors

A = np.array([[2,0],
              [0,3]])
              
e_vals, e_vecs = np.linalg.eig(A)

vec1 = e_vecs[:,0]

lam1 = e_vals[0]

vec2 = e_vecs[:,1]

lam2 = e_vals[1]

t1 = lam1*vec1

t2 = lam2*vec2




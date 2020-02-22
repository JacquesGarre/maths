
v = np.array([2,1])

s = np.array([-3,2])

## Magnitude calculation

v_mag = math.sqrt(v[0]**2 + v[1]**2)

## Direction calculation

v_dir = np.degrees(np.arctan2(v[1], v[0]))

## Addition

z = v + s

## Scalar Multiplication

w = 2 * v

## Dot product Multiplication

d = np.dot(v,s)

d = v @ s *(Python 3.5 +)*

## Theta calculation

cos = (v @ s) / (v_mag * s_mag)

theta = math.degrees(math.acos(cos))

## Cross product Multiplication

p = np.array([2,3,1])

q = np.array([1,2,-2])

r = np.cross(p,q)

# Anakapalli Kanaka Venkata Phaneendra Babu

###### Vishakapatnam

Looking at the breezy mornings everyday in Vizag makes everyone want to go on a long drive to their favourite beach. It’s a daily habit for Vizagites to go for early morning walks, maybe some tea/coffee at RK Beach or a breakfast full of Dosa/Idli. If we want to hang out with friends, the Maggi Point at **Rushikonda Beach** is one of the most sought-after places in Vizag where young people, especially students, come together and have a plateful of Maggi by the beach. No matter what your empty belly desires in the morning, the various eateries in Vizag have some delicious food waiting for you.

---
## Ordered List
The distance between Visakhapatnam Airport to R K Beach is 22 Km by road. 
1. You can also find the distance from Visakhapatnam Airport to R K Beach using other travel options like bus.
2. Subway, tram, train and rail, apart from the trip distance.
3. Refer Directions from Visakhapatnam Airport to R K Beach for road driving directions!
4. Favourite food destination in RK beach is arrived.

---
####  Unordered List
- Muri Mixture. A Muri Mixture vendor at RK Beach.
- Tomato Bajji. Bajji Cart at Double Road. 
- Punugulu. Sumptuous punugulu. 
- Sweet Corn. Sweet corn vendors. 
- Dosa. Dosa with peanut chutney. 
- Liver Kebab. Liver and chicken kebab. 
- Idli. Midnight Idli at Rly Station. 
- Masala Batani. Masala Batani in a bowl.

[ABOUTME](https://github.com/IndraPhani/assignment2-anakapalli/blob/main/AboutMe.md)

---
New section Table
---
|Game Name |Location|Money   |
|----      |----    |--------|
|Swimming  |Hyderabad|200$   |
|Football  |Vizag    |250$   |
|cricket   |chennai  |300$   |
|Golf      |Banglore |350$   |

---
##### Quote Section

---

> "There is no remedy for love but to love more."

*Henry David Thoreau*

> "Lose money for the firm, and I will be understanding. Lose a shred of reputation for the firm, and I will be ruthless."

*Warren Buffett’s*

> "You cannot believe in God until you believe in yourself."

*Swami Vivekananda*

---
### Code Fencing

---
> A sphere (from Greek σφαῖρα—sphaira, "globe, ball") is a geometrical object that is a three-dimensional analogue to a two-dimensional circle. A sphere is the set of points that are all at the same distance r from a given point in three-dimensional space.
[Corresponding link](https://en.wikipedia.org/wiki/Sphere)

~~~
Implementation:

struct point2d {
    ftype x, y;
    point2d() {}
    point2d(ftype x, ftype y): x(x), y(y) {}
    point2d& operator+=(const point2d &t) {
        x += t.x;
        y += t.y;
        return *this;
    }
    point2d& operator-=(const point2d &t) {
        x -= t.x;
        y -= t.y;
        return *this;
    }
    point2d& operator*=(ftype t) {
        x *= t;
        y *= t;
        return *this;
    }
    point2d& operator/=(ftype t) {
        x /= t;
        y /= t;
        return *this;
    }
    point2d operator+(const point2d &t) const {
        return point2d(*this) += t;
    }
    point2d operator-(const point2d &t) const {
        return point2d(*this) -= t;
    }
    point2d operator*(ftype t) const {
        return point2d(*this) *= t;
    }
    point2d operator/(ftype t) const {
        return point2d(*this) /= t;
    }
};
point2d operator*(ftype a, point2d b) {
    return b * a;
}
~~~
[Code link](https://cp-algorithms.com/geometry/basic-geometry.html)
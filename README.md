# Assignment2-Manavarthi
## Sanjay krishna Manavarthi.
### My village <br>
It is **my** **native** place where I was born.

---

## Journey from maryville to Nizamabad.
1. Firstly, book flight ticket from kansas to Hyderabad, Now arrange a ride from Maryville to Kansas    city International Airport.
    1. get your boarding passes and drop your luggage for checkin.
2. Once you board the flight start sleeping for minimum 24hours and you will reach hyderabad.
    1. wakeup at layover and refresh, board again.
3. from hyderabad got to nearest bustation from their board a bus to nizamabad and you reached your destination.

* Items that should be brought for maximum enjoyment.
    * Indian Currency.
    * No need to bring anything we have everything for enjoyment.
[VIP](Aboutme.md)

---

## Table creation.
Food/drinks that I would recommend someone try.
| Food/Drinks | Location | Cost |
|--------------|----------|------|
| pepsi        | Canteen  |free  |
| French fries | McDonalds|$3.00 |
| Burger       | McDonalds|$3.00 |
| chocolet milk| canteen  |free  |

---

## Pithy Quotes.
> I will never be happy without having someone.Going to sleep alone kills me.

> Life is too short for long-term grudges.

-*Elon Musk*

---

## Code Fencing
> Fibonacci numbers are named after the Italian mathematician Leonardo of Pisa, later known as Fibonacci.

>The Fibonacci sequence appears in Indian mathematics in connection with Sanskrit prosody, as pointed out by Parmanand Singh in 1986.

>The Fibonacci sequence appears in Indian mathematics in connection with Sanskrit prosody, as pointed out by Parmanand Singh in 1986.

[Link to the source](https://en.wikipedia.org/wiki/Fibonacci_number)
Code for Fibonacci series

pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}

[Quick link for the code](https://cp-algorithms.com/algebra/fibonacci-numbers.html)

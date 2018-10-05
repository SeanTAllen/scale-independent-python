# Scale Independent Python

Scale Independent Python: How to scale your Python application without any code changes.

## Abstract

Have you ever written an application only to find yourself rewriting it later so it can scale? Many of us have. In this talk, you’ll learn scale independent computing; what it is and how it can help you more easily scale your applications.

Scaling applications is hard. Our typical approaches all come with tradeoffs that we wish we didn’t have to make. There is a better way, scale-independent computing. Based on ideas from Pat Helland’s paper “[Beyond Distributed Transactions](https://queue.acm.org/detail.cfm?id=3025012),” scale-independent computing allows application developers to write their code without regard to scale and then run it on a scale-aware platform. The idea is relatively simple, the code you write should be able to run across any number of Python processes without you having to change any of your code. During this talk, you’ll learn the core ideas of scale-independence and see an example scale-independent application in action.

## Versions of this talk

* PyGotham 2018 - [Slides]()

## Related Talk

* [Pat Helland and Me: How to build stateful distributed applications that can scale almost infinitely](https://github.com/SeanTAllen/pat-helland-and-me)

## Deeper dive into Scale Independent computing

* [Wallaroo Scale-Independent Computing](https://vimeo.com/270509076)

## Links 

* [Wallaroo](https://github.com/wallaroolabs/wallaroo)
* [Wallaroo Labs' Twitter](https://twitter.com/wallaroolabs)
* [My Twitter](https://twitter.com/seantallen)
* [My Personal Website](https://www.monkeysnatchbanana.com/)
* [Pat Helland's Twitter](https://twitter.com/pathelland)

## Wallaroo use-cases and examples

- [Scaling Pandas with Wallaroo](https://blog.wallaroolabs.com/2018/09/make-python-pandas-go-fast/)
- [Event triggered customer segmentation](https://blog.wallaroolabs.com/2018/07/event-triggered-customer-segmentation/)
- [Chatbot spam detection](https://blog.wallaroolabs.com/2018/07/detecting-spam-as-it-happens-getting-erlang-and-python-working-together-with-wallaroo/)
- [Detecting trends in data streams](https://blog.wallaroolabs.com/2018/06/stream-processing-trending-hashtags-and-wallaroo/)
- [Still more...](https://blog.wallaroolabs.com/categories/wallaroo-in-action/)

## References

* [Life Beyond Distributed Transactions - 2007 version](http://www-db.cs.wisc.edu/cidr/cidr2007/papers/cidr07p15.pdf)
* [Life Beyond Distributed Transactions - 2016 version](https://queue.acm.org/detail.cfm?id=3025012)
* [Horizontal and Vertical Scaling](https://en.wikipedia.org/wiki/Scalability#Horizontal_and_vertical_scaling)

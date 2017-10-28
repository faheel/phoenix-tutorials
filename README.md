# The Phoenix Framework

Have you ever wanted to build applications that are fast and capable of handling millions (yes, millions!) of connections at the same time? Have you ever wanted to just build your web application instead of spending countless hours just configuring your environment? Have you ever wanted fault-tolerant, self-healing applications that keep working even though the application process may have crashed?

Congratulations! You've come to the right place.

Phoenix is a full stack framework that lets you easily build fast, concurent and fault tolerant applications.

---

#### Installation

To get started with with Phoenix, you'll need to install

* **Elixir** \(programming Language\)
* **Postgres** \(for managing the database Phoenix creates\)
* **Hex** \(package manager crucial for installing Phoenix\)

and then from there, installing Phoenix is pretty straightforward. The Phoenix Guides provide a great tutorial on how to install the above and then Phoenix. Head over [there](https://hexdocs.pm/phoenix/installation.html "Installation - Phoenix") and then come back.

---

#### A Dry Run

Let's create a simple web app using the cool generators Phoenix provides by default. These generators are an easy way to build boilerplate code and hit the ground running as fast as possible. They are also an awesome tool to learn the framework.

So open up a new terminal in the directory you like and type the following command, without the `$` of course:

```bash
$ mix phx.new simpleapp
```

`mix` is basically a command line tool that helps you run Phoenix tasks with ease, click [here](https://hexdocs.pm/phoenix/phoenix_mix_tasks.html#content) to know more about mix tasks.


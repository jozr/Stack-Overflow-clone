#Stack Overflow Clone
Replicates functional structures from [Stack Overflow](http://www.stackoverflow.com/)

##Tools
Ruby 2.1.2<br />
ActiveRecord<br />
Rails 4.1.6<br />
PostgreSQL<br />

##Setup
In your terminal, clone this repository:

```console
$ git clone https://github.com/jozw/Stack-Overflow-clone.git
```

Make sure you've installed [PostgreSQL](http://www.postgresql.org/download/).

Install all the dependencies:

```console
$ bundle install
```

Set up the databases on your local machine:

```console
$ rake db:create
$ rake db:schema:load
```

Start the rails server:

```console
$ rails s
```
Now, it will be available at `http://localhost:3000`.

##License
MIT
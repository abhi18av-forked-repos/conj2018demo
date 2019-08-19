# Pathom Demo for Clojure Conj 2018

###  Hard-coded data

```clojure
[:all-emails]


[{:all-emails
  [:full-name]}]
```

### YouTube API

For `youtube` access you'll need to add an `access token` - the code for that is in `pathom-youtube` package.

```clojure
[{[:youtube.user/username "clojuretv"]}]

```
### SpaceX API

```clojure
  [{:spacex/all-launches
    [:spacex.launch/flight-number
     :spacex.launch.links/video-link]}]
```

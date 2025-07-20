# AI Evals

Trying to bring a tiny bit of rigor to AI deep research tool evaluations.

## Evaluations

### 01. Laneway Houses

"Find out why some laneway/coach houses can be sold on their own in Vancouver and some can't"

A good answer would touch on:

- character retention program
- coach house stuff (which I believe is RT only)

#### 2025-06-24

**Claude 4.0 Sonnet:** gets the broad strokes right but makes up some stuff about the pre-laneway-house era (totally unrelated CityHallWatch citation, oof) and mistakenly thinks the character house program ended when it didn't.

Not great.

#### 2025-06-25

**Claude 4.0 Opus:**

"Examples demonstrate viability but limited application" section is incorrect. But otherwise pretty good summary of laneways. Doesn't touch on the RT coach house thing.

#### 2025-06-26

**Gemini 2.5 Pro:**

TODO analyze this

#### 2025-07-17

**Mistral:**

Not bad? Includes a bunch of unrelated stuff and doesn't go into too much detail, but it gets the main points right.

### 02. Commercial Drive restaurant recommendations

"Find me a restaurant for dinner on Commercial Drive in Vancouver. I like Mezcaleria and Absinthe Bistro but I'm a little tired of them. Ideally somewhere that doesn't require reservations"

Good answer will suggest a few decent places but *not*:

- places that only do drinks with a few snacks (Flamingo Room, Storm)
- places that have closed permanently (Carthage Cafe)
- Mezcaleria and Absinthe; I already suggested those

A great answer will avoid places like Lunch Lady which are so busy that you effectively need a reservation, or at least mention that.

#### 2025-07-17

**Mistral:**

Not very good. Big list of restaurants, not picky at all, included Storm, Flamingo Room, Mezcaleria.

**Claude:**

Quite good BUT it suggested the Flamingo Room as 1 of 4. Otherwise great.
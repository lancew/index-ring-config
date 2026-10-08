# Index Ring config page

Static settings page for the Index Ring Pebble app. Pebble opens it from the
app's settings (the `configurable` capability), the user pastes their Nenya
Firebase refreshToken, and the page hands it back to PebbleKit JS via
`pebblejs://close#...`.

Served at: https://lancew.github.io/index-ring-config/config.html

This page contains no secrets or credentials. It only collects a value the user
enters; the value is stored on the phone (PebbleKit JS `localStorage`), never
here.

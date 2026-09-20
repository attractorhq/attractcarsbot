# AttractCarsBot — crawler identity endpoint

This repository publishes one static page: the public identity and control
documentation for **AttractCarsBot**, the web crawler operated by Attractor Oy
(Finland, business ID 3592322-7).

It exists because a crawler that names a page in its `User-Agent` must actually
serve that page. AttractCars refuses to fetch any public address unless the URL
it advertises returns HTTP 200 and names the crawler — the check is enforced in
code, not by policy.

Served at <https://attractorhq.github.io/attractcarsbot/>.

Contact, takedowns and rate complaints: info@attractor.fi

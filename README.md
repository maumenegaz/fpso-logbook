# fpso-logbook
FPSO Marine Operations Logbook API

An FPSO (Floating Production, Storage and Offloading) is a specialized offshore unit, whose purpose is to produce oil (and gas in most cases), store and offload (receive an off-take tanker) during the operational lifecycle.

This project is designed as a microservice, whose purpose is to standardize and facilitate the logging of events occurring on the Marine department of the vessel.

Log keeping is not only a maritime tradition, but a legal requirement, as all the vessels with an IMO number are required to comply to a multitude of regulations (flag, port, class, P&I and so forth).

The design evolves around the usual workflow of log keeping: a clerk inputs log entries, specifying the date and time of the event, and the details. The digital logbook incorporates additional trust to the reporting, as one can take advantage of hashing (like in a blockchain) to ensure the sequence of events and reporting.

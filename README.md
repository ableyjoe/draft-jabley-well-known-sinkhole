draft-jabley-well-known-blackhole
================================

   A common method for dealing with unwanted traffic is to direct that
   traffic at nominated addresses within a network that are null-routed;
   that is, packets with such destination addresses are discarded
   silently by routers with a null route for that destination
   configured.  These addresses are colloquially known as black holes,
   by analogy with the same term used in astrophysics to describe a void
   in spacetime where gravity prohibits anything from escaping once
   having crossed the event horizon.  Alternatively, traffic may be
   redirected to quarantine, to isolate, contain and limit any
   potentially harmful effects.  Quarantine addresses may permit some
   bidirectional communications whereas a black hole may receive, but
   never originate traffic.

   This document describes an Internet-scope anycast black hole and
   quarantine service with associated well-known, permanent IPv4 and
   IPv6 address assignments, and provides guidance both for network
   operators and for those wishing to use the service to discard
   unwanted traffic efficiently.


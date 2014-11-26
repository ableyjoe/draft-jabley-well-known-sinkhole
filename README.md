draft-jabley-well-known-sinkhole
================================

    A common method for dealing with unwanted traffic is to direct that
    traffic at nominated addresses within a network that are null-routed;
    that is, packets with such destination addresses are discarded
    silently by routers with a null route for that destination
    configured.  These addresses are colloquially known as sinkholes, by
    analogy with the same term used in Physical Geography to describe a
    hole in the ground formed by some form of collapse of the surface
    layer, into which objects may fall and be lost forever.

    This document describes an Internet-scope anycast sinkhole service
    with associated well-known, permanent IPv4 and IPv6 address
    assignments, and provides guidance both for network operators and for
    those wishing to use the service to discard unwanted traffic
    efficiently.


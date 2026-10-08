# Sources of the dimensions

The dimensions are those of these standards, tabulated for this library
(the values are the standards' facts; no other collection's tables were
copied):

- ISO 4762, hexagon socket head cap screws: head diameter and height
  (maximum), socket size (nominal), socket depth (minimum), preferred
  lengths.
- ISO 4017, hexagon head screws with the thread up to the head: width
  across flats and head height (nominal), preferred lengths.
- ISO 10642, hexagon socket countersunk head screws: theoretical head
  diameter, head height (maximum), socket size, socket depth (minimum),
  preferred lengths (including the head).
- ISO 4032, hexagon regular nuts (style 1): width across flats, height
  (maximum).
- ISO 7089, plain washers, normal series: hole diameter (minimum), outside
  diameter (maximum), thickness (nominal).
- ISO 261 and ISO 724: the coarse thread pitches (parameter P).

The geometry is simplified for assemblies: no threads, chamfers, fillets
or under-head radii. Check critical dimensions against the standard you
work to.

The generator: tools/libraries/make-fastener-library.py in Mitcad's
repository.

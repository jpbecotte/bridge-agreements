# Points counting

tpts = max ( hcp + length_pts, hcp + fit_pts)

hcp = as => 4, king => 3, queen => 2, jack => 1

length_pts = for all suits (add (suit.length - 4))

fit_pts = if fit_agreed: then: any (void: 4, singleton: 3, doubleton: 1)

dataTPY_DME_X.npy      3,500,000 * 41 matrix in np.array type

  3,500,000 pieces of T, P, Yi (41 dimensional vector) data indicating thermochemical state of DME/air mixture.

dataTPY_DME_Y.npy      3,500,000 * 41 matrix in np.array type

  3,500,000 pieces of T, P, Yi (41 dimensional vector) data, calculated from dataTPY_DME_X.npy.

How to get Y data from X?

  We used Cantera.IdealGasConstPressureReactor to evolve delta_t = 1e-6 s.

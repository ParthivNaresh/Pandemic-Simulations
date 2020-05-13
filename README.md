# Simulating a Pandemic
Visually simulating how a pandemic could spread through a population by changing hyperparameters like size, infection rate, lethality, etc.

## Libraries/Packages
 - Python 3
   - Pandas
   - NumPy
   - Matplotlib
   - Numba

## Scenarios

### First scenario
- [x] The first scenario emulates no social distancing in which a virus spreads rampant through the population, providing immunity for everyone who doesn't die.

![No Social Distancing Simulation](/Simulation_0.gif)

### Second scenario
- [ ] The second scenario emulates complete social distancing in which people keep a constant distance (when possible) from those who are infected and symptomatic.

### Third scenario
- [ ] The third scenario emulates some social distancing in which some people choose to comply with social distancing guidelines and some don't.

### Fourth scenario
- [ ] The fourth scenario includes a common destination that the population visits (emulating a supermarket or bank).

## Improvements/Additions

### Data Visualization
- [x] Add contact tracing abilities when a patient is infectious.

- [ ] Add tracing to find Patient Zero.

### Speed
- [x] Improve the efficiency by changing over to NumPy instead of Pandas and compile with Numba.

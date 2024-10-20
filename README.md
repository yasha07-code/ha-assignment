 this is the code for sample signal
 
# Generate a sample AC signal for testing purposes
sample_rate = 1000
t = np.linspace(0, 1, sample_rate, endpoint=False)
signal = np.sin(2 * np.pi * 50 * t) + 0.2 * np.sin(2 * np.pi * 150 * t)

# Save the signal for testing
np.savetxt('sample_signal.txt', signal)

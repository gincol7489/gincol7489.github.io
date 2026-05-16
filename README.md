# gincol7489.github.io
Trial 
import matplotlib.pyplot as plt
import seaborn as sns

# Example: Plotting fraud transaction patterns
sns.countplot(data=df, x='is_fraud')
plt.title('Distribution of Fraudulent vs. Legitimate Transactions')

# Save the graph as an image file
plt.savefig('fraud_distribution.png', dpi=300, bbox_inches='tight')

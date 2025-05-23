Associated Code repository for,

# Hierarchical Gaussian Process-Based Bayesian Optimization for Materials Discovery in High Entropy Alloy Spaces

Sk Md Ahnaf Akif Alvi, Jan Janssen, Danial Khatamsaz, Danny Perez, Douglas Allaire, Raymundo Arroyave


Bayesian optimization (BO) is a powerful and data-efficient method for iterative materials discovery and design, particularly valuable when prior knowledge is limited, underlying functional relationships are complex or unknown, and the cost of querying the materials space is significant. Traditional BO methodologies typically utilize conventional Gaussian Processes (cGPs) to model the relationships between material inputs and properties, as well as correlations within the input space. However, cGP-BO approaches often fall short in multi-objective optimization scenarios, where they are unable to fully exploit correlations between distinct material properties. Leveraging these correlations can significantly enhance the discovery process, as information about one property can inform and improve predictions about others. This study addresses this limitation by employing advanced kernel structures to capture and model multi-dimensional property correlations through multi-task (MTGPs) or deep Gaussian Processes (DGPs), thus accelerating the discovery process. We demonstrate the effectiveness of MTGP-BO and DGP-BO in rapidly and robustly solving complex materials design challenges that occur within the context of complex multi-objective optimization over FCC FeCrNiCoCu high entropy alloy (HEA) spaces, where traditional cGP-BO approaches fail. Furthermore, we highlight how the differential costs associated with querying various material properties can be strategically leveraged to make the materials discovery process more cost-efficient.

Link to Code Ocean Capsule : https://codeocean.com/capsule/9540168/tree

Dataset DOI:  https://doi.org/10.5281/zenodo.15149719

Paper DOI: https://doi.org/10.1016/j.actamat.2025.120908

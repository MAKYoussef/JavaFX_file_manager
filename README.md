# \# Projet\_POO\_AV: Favorite File Manager

# 

# \## Project Description

# 

# This is a \*\*standalone desktop application\*\* developed in \*\*Java\*\* with a \*\*JavaFX\*\* graphical user interface. Its primary goal is to allow the user to easily list, organize, and search through a personal collection of \*\*favorite files\*\*.

# 

# The application uses a system of \*\*Tags\*\* (keywords) to classify files and relies on a \*\*Relational Database (Oracle)\*\* via JDBC for persistence and management of metadata (title, author, tags, summary).

# 

# \*\*\*

# 

# \## Core Features

# 

# \* \*\*File Tagging (CRUD)\*\*: Adding a favorite file, associating detailed descriptions (title, author, tags, summary), modifying, and deleting the file entry.

# \* \*\*Advanced Search\*\*: Allows users to search for favorite files by title, author, or tag.

# \* \*\*Property Listing\*\*: Displays collection statistics, including the total number of favorite files, a list of all authors, and a count of files associated with each tag.

# \* \*\*Data Persistence\*\*: Uses an Oracle Database instance to reliably store all metadata and relationships.

# 

# \*\*\*

# 

# \## Technologies Used

# 

# | Category | Technology | Description |

# | :--- | :--- | :--- |

# | \*\*Language\*\* | Java | The main programming language for the project. |

# | \*\*User Interface\*\* | JavaFX | The framework used to create the graphical user interface. |

# | \*\*Database\*\* | Oracle Database | The relational database management system (RDBMS) used. |

# | \*\*Connectivity\*\* | JDBC | The Java API used for connecting to the database and executing SQL queries. |

# 

# \*\*\*

# 

# \## Repository Structure

# 

# The repository follows a standard structure for a standalone Java project to facilitate compilation and source verification.

# 

# | Folder/File | Content |

# | :--- | :--- |

# | \*\*`src/`\*\* | Contains all the application's Java source code (`.java` files). |

# | \*\*`lib/`\*\* | Contains external dependencies required for the project (Oracle JDBC driver, JavaFX JARs). |

# | \*\*`Rapport\_de\_projet.pdf`\*\* | Detailed implementation report for the project. |

# | \*\*`TP Noté POO AV 2025.pdf`\*\* | The official project statement. |

# | \*\*`README.md`\*\* | This document. |

# 

# \*\*\*

# 

# \## Execution Guide

# 

# To run this project, you must configure the classpath to include the libraries in the `lib/` folder.

# 

# 1\.  \*\*Prerequisites\*\* ⚙️: Ensure that the \*\*JDK\*\* (version 11+) and the \*\*Oracle JDBC driver\*\* are installed and configured.

# 2\.  \*\*Database Connection\*\* 💾: Verify that the Oracle instance is accessible and that the connection details used in the source code are valid.

# 3\.  \*\*Compilation \& Launch\*\* 🚀: The project must be compiled by including the path to the JavaFX JARs and the dependencies


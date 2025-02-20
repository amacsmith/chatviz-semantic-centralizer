# ChatViz Semantic Centralizer

A free and open-source tool for aggregating, semantically searching, and visualizing chatbot conversation data.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd chatviz_semantic_centralizer
   ```

2. Create a virtual environment (recommended):

   ```bash
   python3.11 -m venv venv
   ```

3. activate scoped environmeent:

   ```bash
   source venv/bin/activate  # On Linux/macOS
   venv\Scripts\activate  # On Windows
   ```

4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the Dashboard:

   ```bash
   python scripts/run_dashboard.py
   ```

## Usage

   Place your chatbot conversation data (JSON or CSV) in the data/raw folder.
   Run the ingestion script: python scripts/run_ingestion.py
   Run the index building script: python scripts/build_index.py
   Access the dashboard at http://localhost:8501.

## Documentation

   See the docs folder for detailed documentation.
   
## License

[MIT License](License)

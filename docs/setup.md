## Set Up Environment

- Make sure you have `python >= 3.10` installed.
- If using macOS, you may need to install `hdf5` (e.g., via `brew install hdf5`).
- Install poetry: `pip install 'poetry>=1.8'`
- Install the project dependencies: `poetry update`
- Enter the virtual environment: `poetry shell`
- Run all tests: `poe test_all`
- Enable pre-commit:  `pre-commit install`
- Do you want to add a new dependency? `poetry add foo-pkg --group dev`

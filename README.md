# Installation
It's a toy example of building wheel.

1. Clone the Repository:
   ```bash
   git clone https://github.com/waleking/toy_wheel 
   cd toy_wheel 
   ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate 
    ```
3. Install the build tools:

    ```bash
    pip install --upgrade build
    ```

4. Build the package: Run the following command to build the package. This will create a .whl file in the dist/ directory.

    ```bash
    python -m build
    ```

5. Install the package: Install the package using the .whl file generated in the dist/ folder:

    ```bash
    pip install dist/toy_wheel-0.1.0-py3-none-any.whl
    ```

# Usage
Once the package is installed, you can use the hello() function from the toy_wheel package:
```bash
python -c "from toy_wheel import hello; print(hello())"
```

This will print:
```bash
Hello from toy wheel!
```

# Rebuild and reinstall
```bash
python -m build
pip install dist/toy_wheel-0.1.0-py3-none-any.whl
```

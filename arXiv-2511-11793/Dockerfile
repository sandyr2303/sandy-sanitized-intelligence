FROM python:3.11-slim

WORKDIR /app

# Install dependencies
RUN pip install --no-cache-dir asyncio jsonlines

# Copy implementation and benchmark suite
COPY implementation.py .
COPY benchmark.py .

# Run the benchmark by default
CMD ["python", "benchmark.py"]

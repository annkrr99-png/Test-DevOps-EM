FROM python:3.11-slim
WORKDIR /app
RUN adduser --system --group --no-create-home appuser
COPY --chown=appuser:appuser app.py .
EXPOSE 8080
USER appuser
CMD ["python", "app.py"]

# Incremental Loading Strategy

1. Read last load timestamp
2. Extract only new records
3. Load data into staging table
4. Merge into target table
5. Update watermark value

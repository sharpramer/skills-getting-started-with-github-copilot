# Validate student is not already signed up
if email in activity["participants"]:
    raise HTTPException(status_code=400, detail="Student is already signed up")
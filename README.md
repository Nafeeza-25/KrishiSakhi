cd ..
cat > README.md <<'EOF'
Krishi Sakhi MVP - Farmer profile + advisory demo
Run backend: python3 backend/app.py
Open frontend/index.html in browser and call backend at http://127.0.0.1:5000/advice
EOF
git add .
git commit -m "initial repo structure"
git push origin main

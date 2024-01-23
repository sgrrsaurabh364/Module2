from flask import Flask, render_template, request, jsonify
import model  # Import your model.py file

app = Flask(__name__)

@app.route("/", methods=["GET", "POST"])
def upload_file():
    if request.method == "POST":
        try:
            file = request.files["data_file"]
            data = json.load(file)
            results = model.probe_model_5l_profit(data)  # Call your model function
            return jsonify(results)  # Return JSON results
        except Exception as e:
            return jsonify({"error": str(e)})
    return render_template("upload.html")

@app.route("/results")
def display_results():
    results = request.args.get("results")  # Retrieve results from URL query string
    # Process and format results for display
    return render_template("results.html", results=results)

if __name__ == "__main__":
    app.run(debug=True)

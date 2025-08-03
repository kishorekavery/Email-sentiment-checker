# Email-sentiment-checker
Traditional and advance approach of sentiment analysis of emails 
🚀 SETUP INSTRUCTIONS FOR GEMINI LLM INTEGRATION:
    
    1. Get Gemini API Key:
       - Go to https://makersuite.google.com/app/apikey
       - Create a new API key
    
    2. Install required packages:
       pip install google-generativeai nltk dotenv
    
    3. Set up API key (choose one method):
       Method A - create dotenv file:
       GEMINI_API_KEY="your_api_key_here"
       
       Method B - Direct initialization:
       analyzer = AdvancedSentimentAnalyzer(gemini_api_key="your_api_key_here")
    
    4. Usage Examples:
       # Traditional analysis only
       result = analyzer.process_json_input(json_string)
       
       # Enhanced analysis with Gemini LLM
       result = analyzer.process_json_input_with_llm(json_string, use_gemini=True)
    
    📈 ENHANCED FEATURES WITH GEMINI:
    - Contextual tone analysis (Professional, Casual, etc.)
    - Psychological insights and stress indicators
    - Business context understanding
    - Detailed reasoning and explanations
    - Advanced actionable recommendations
    - Consensus scoring between traditional and LLM analysis
    - Key phrase extraction
    - Follow-up suggestions
    """

# Real-time-sign-language-to-text-conversion-using-MediaPipe-and-Machine-Learning
Recognizing the transformative power of technology in this domain, this master project paper delves into the realm of sign language recognition, with a focus on American Sign Language (ASL) finger spelling alphabets .
The field of computer vision and machine learning has witnessed remarkable advancements in recent years, revolutionizing the way we perceive and interact with visual data. One of the areas where these technologies hold profound potential is in sign language recognition and interpretation, particularly beneficial for the deaf and hard of hearing community. Sign language, as a unique and expressive form of communication, bridges the gap between different modes of expression, enabling seamless interactions between individuals who communicate using spoken language and those who employ sign language [1].
Recognizing the transformative power of technology in this domain, this master project paper delves into the realm of sign language recognition, with a focus on American Sign Language (ASL) finger spelling alphabets is in Fig1. The goal is to develop efficient and accurate models that can automatically convert sign language finger spelling gestures into textual representations in real time. By doing so, this project aims to enhance communication accessibility, promote inclusion, and empower individuals who rely on sign language as their primary mode of expression.


![image](https://github.com/jamescheriyan/Real-time-sign-language-to-text-conversion-using-MediaPipe-and-Machine-Learning/assets/63226335/423f70df-4d13-4a10-a0d4-9d3ca0cdb9f8)



Fig 1 - ASL fingerspelling [2]
When compared to general sign language recognition, fingerspelling recognition is somewhat more constrained due to its use of a limited range of handshapes. In American Sign Language (ASL), fingerspelling is performed with a single hand, unlike certain other sign languages, which results in less concern about hand occlusion [3].
This paper undertakes a comprehensive exploration of various deep learning models, tools, and methodologies to achieve the ambitious objective of real-time sign language to text conversion. It involves the use of pre-trained models, fine-tuning, and custom architectures, leveraging frameworks like TensorFlow and Keras. Additionally, the project involves the integration of computer vision libraries such as OpenCV and MediaPipe, which play pivotal roles in accurately extracting features from visual data and tracking hand movements for precise gesture recognition.
In the following sections, the paper delves into the methodologies, experimental setups, results, and implications of the research, shedding light on the intricacies of sign language recognition and the transformative potential of technology in promoting communication inclusivity.

# Real-time result of sign language to text conversion using MediaPipe and ML


https://github.com/jamescheriyan/Real-time-sign-language-to-text-conversion-using-MediaPipe-and-Machine-Learning/assets/63226335/8c3e63cb-c524-4c19-9d0a-1b39c0d746c3



# Discussion
This study compared various deep learning models for real-time conversion of American Sign Language (ASL) gestures into text. Using pre-trained models, custom architectures, and fine-tuning techniques, we evaluated their applicability. The findings provide insights into their capabilities and constraints. 
Among pre-trained models, MobileNet stood out with 93.83% validation accuracy, making it suitable for ASL gesture classification. Extensive testing revealed a 98.72% test accuracy, indicating its strong generalization on new data, making it ideal for real-time tasks.
The custom CNN model achieved a 96.77% validation accuracy and 97.48% test accuracy, showing promise in accurate ASL gesture recognition. Impressive precision, recall, and F1-scores were observed, though specific classes suggested room for improvement. The CNN with MediaPipe, validating at 98.843%, excelled on both validation and test data, with a 99.37% test accuracy. Its robust precision, recall, and F1-scores showcased its efficacy in ASL gesture identification, leveraging MediaPipe's hand landmarks.
Fine-tuning MobileNet boosted validation accuracy to 95.21%, hinting at task-specific adjustments. With a 98.37% test accuracy, it remains capable of ASL gesture classification. The model's classification report provided insights into class-specific performance.
Based on this evaluation, the CNN with MediaPipe emerged as the top choice for real-time ASL to text conversion. Its consistent accuracy and seamless integration with MediaPipe's hand tracking make it a practical solution.

# Conclusion 
This research comprehensively explores and compares various deep learning models for converting ASL alphabet gestures into text. The paper assesses pre-trained models, custom architectures, and fine-tuning methods, emphasizing real-time applicability. The thorough analysis conducted in this research led us to select the CNN with MediaPipe model as the optimal choice for accurate and efficient ASL to text conversion in real-time scenarios. The real-time ASL sign language to text converter showcases our findings by accurately predicting ASL gestures, forming words, and suggesting spellings, thus benefiting sign language users. This study emphasizes tailored model selection, fine-tuning, and advanced techniques like MediaPipe for enhanced ASL alphabet gesture recognition, thereby contributing to better assistive technologies and fostering inclusivity by bridging communication gaps. Future work in this domain could explore further improvements to model accuracy, especially for challenging gestures with similar hand movements. Additionally, the application's usability and accessibility can be enhanced by incorporating user-friendly interfaces and expanding language support. Ultimately, our research contributes to the advancement of assistive technologies and facilitates seamless communication between diverse communities.


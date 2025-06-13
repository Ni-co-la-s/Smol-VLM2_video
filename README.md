
# Smol-VLM2_video 


##Prompt 

"""
You are analyzing a driving video from the perspective of the vehicle recording the video (the ego vehicle).
In 2-3 short factual sentences, state:
-Vehicle types seen (cars, trucks, buses, etc.).
-What the ego vehicle (the recording vehicle) is doing (driving, stopped, turning, etc.).
-Presence of pedestrians or cyclists.
-Static obstacles.
-Road conditions.
-Weather.
-Visibility.
Do not describe the appearance or aesthetics. Be concise.
"""

## Config

nvidia 4070 super 
HuggingFaceTB/SmolVLM2-256M-Video-Instruct: 4.4s/iteration
HuggingFaceTB/SmolVLM2-500M-Video-Instruct: 4.6s/iteration
HuggingFaceTB/SmolVLM2-2.2B-Instruct: 5.3s/iteration
Qwen/Qwen2.5-VL-3B-Instruct 10s/iteration. 1fps: 360*420 resizing




## Result 1

https://github.com/user-attachments/assets/0ceb14b5-2623-48cf-b06d-f22f4e3417f6



HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving on a wet road at night.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: The ego vehicle is driving down the road, passing by a pedestrian crossing, and the road is wet from recent rain. The weather is overcast, and visibility is poor due to the rain.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a dark street at night, passing other vehicles, including cars and trucks. The road conditions are wet, and the visibility is low due to the darkness and rain. There are no pedestrians or cyclists visible in the video. The static obstacles are traffic lights, which are red, indicating that the vehicles must stop.

Qwen/Qwen2.5-VL-3B-Instruct
The ego vehicle is driving on a city street at night. The road is wet and reflective due to recent rain. There are multiple cars and trucks visible in the traffic. The traffic lights are red, indicating that vehicles must stop. There are no pedestrians or cyclists visible. The road has white lane markings and a crosswalk. The visibility is clear, with streetlights illuminating the scene.


## Result 2



https://github.com/user-attachments/assets/ad42d53b-8fe2-44b7-a4af-c41ce8037799


HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving on a wet road, stopped at a red light, and is seen turning left.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: The ego vehicle is driving down the road, passing by a stop sign and a traffic light, and then turning left onto a crosswalk. There are no pedestrians or cyclists visible. The road is wet, and the weather is overcast. The visibility is good, and the road conditions are clear.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a city street at night, passing other vehicles, including cars and trucks. The vehicle is stopped at a red light, and the surrounding environment includes parked cars, pedestrians, and a bus. The road conditions are wet, and the visibility is low due to the darkness and the presence of streetlights.

Qwen/Qwen2.5-VL-3B-Instruct
The ego vehicle is driving on a city street at night. It is following a bus and other cars. There are no pedestrians or cyclists visible. The road has multiple lanes with traffic lights and signs. The weather appears to be clear, and visibility is good.




## Result 3



https://github.com/user-attachments/assets/20e8bce4-37c0-46a7-9b67-49176ae9d6b7


HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving on a busy street with pedestrians and cyclists.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: A black car, a white bus, and a blue truck are seen driving on the road. There are no pedestrians or cyclists visible. The road is clear and there are no visible obstacles. The weather is sunny with clear skies.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a city street, passing other vehicles including cars and trucks. Pedestrians are present on the sidewalk, and there are traffic lights at intersections. The road conditions are clear, and the weather is sunny. The visibility is good, and the ego vehicle is driving in the right lane.

Qwen/Qwen2.5-VL-3B-Instruct
A black car is driving on the road. The ego vehicle is driving. There are no pedestrians or cyclists. There are buildings and trees as static obstacles. The road is clear with no visible potholes. The weather is clear with no clouds. The visibility is good.


## Result 4



https://github.com/user-attachments/assets/8334cfa8-ac6d-4628-b0b8-bd945e050f52


HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving on a busy street with traffic lights and pedestrians. The road is clear and sunny, and the sky is clear with a few clouds. The environment is bustling with activity, and the road is well-maintained. The presence of pedestrians or cyclists suggests that the area is a popular tourist spot.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: White car, stopped, turning, pedestrians, traffic lights, clear weather, good visibility.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a city street, passing by other vehicles including cars and trucks. The vehicle is stopped at a red traffic light, and there are pedestrians visible on the sidewalk. The road conditions are good, with clear visibility and no visible obstacles. The weather is clear with a blue sky.

Qwen/Qwen2.5-VL-3B-Instruct
The ego vehicle is driving on a city street. There are cars and a bus on the road. A cyclist is riding down the street. There are buildings and trees along the street. The weather is clear and sunny. The visibility is good.


## Result 5



https://github.com/user-attachments/assets/142a4eed-6eae-438f-b456-299f7fcf98c1


HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving on a busy road with pedestrians and cyclists.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: The ego vehicle is driving down the street, passing by pedestrians and cyclists. The road is clear, and the weather is sunny. The visibility is good, and the road conditions are clear.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a city street, passing by other vehicles, including cars and trucks. There are pedestrians walking on the sidewalk and cyclists riding on the road. The weather is clear with a blue sky, and the road conditions are good with no visible potholes or debris. The visibility is good, and the ego vehicle is driving at a moderate speed.

Qwen/Qwen2.5-VL-3B-Instruct
The ego vehicle is driving on a road with buildings and trees on both sides. There are cars and trucks on the road. The weather is clear and sunny. Visibility is good.


## Result 6



https://github.com/user-attachments/assets/ad43402d-f394-4af3-8e3b-9581b38a45f4


HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving on a busy road with traffic and pedestrians. The recording vehicle is stopped at a traffic light, and the road conditions suggest it is a busy intersection. The static obstacles are pedestrians or cyclists. The weather is clear and sunny, and visibility is good.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: A silver car, a white car, and a black car are seen. The ego vehicle is driving down the street, passing by pedestrians and cyclists. The road is clear, and the weather is sunny. The visibility is good.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a city street with other vehicles, including cars and trucks. The vehicle is stopped at a red traffic light. There are pedestrians and cyclists present, but no static obstacles. The road conditions are good, and the weather is clear. The visibility is good, and the sky is blue.

Qwen/Qwen2.5-VL-3B-Instruct
The ego vehicle is stopped at a traffic light. There are cars and trucks on the road. The weather is clear with no clouds in the sky. Visibility is good.


## Result 7


https://github.com/user-attachments/assets/d99a5c4a-2f9c-4220-9c04-eb49c858c4be


HuggingFaceTB/SmolVLM2-256M-Video-Instruct:
Assistant: The ego vehicle is driving down a city street at night. It's stopped at a red light, and the road is lit by streetlights. The road is also wet, and the foggy conditions suggest it might be a rainy day. The environment is dimly lit, and the road is not visible.

HuggingFaceTB/SmolVLM2-500M-Video-Instruct:
Assistant: Car, stopped, turning, pedestrians, no cyclists, wet road, dark, visibility poor, wet street.

HuggingFaceTB/SmolVLM2-2.2B-Instruct
Assistant: The ego vehicle is driving on a city street at night, passing other vehicles, including cars and trucks. The road conditions are wet, and the visibility is low due to the darkness and rain. There are no pedestrians or cyclists visible in the video. The ego vehicle is driving in the right lane and is passing a red traffic light.

Qwen/Qwen2.5-VL-3B-Instruct
The video shows a nighttime urban setting with multiple vehicles on the road. The ego vehicle appears to be driving, as indicated by the changing perspective and the presence of other vehicles ahead. There are no visible pedestrians or cyclists in the frames. Static obstacles include traffic lights and street signs. Road conditions seem clear, and visibility is good due to artificial lighting. The weather appears to be clear, with no signs of rain or fog.


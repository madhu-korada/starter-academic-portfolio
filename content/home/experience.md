+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.



[[experience]]
  title = "Research Engineer"
  company = "Hi-tech Robotic Systemz Ltd"
  company_url = "https://www.hitechroboticsystemz.com/"
  location = "Gurgaon, IN"
  date_start = "2019-06-01"
  date_end = ""
  description = """
  Responsibilities include:
  * Worked closely with hardware team for a radar integration with Novus Aware device to add a new Forward Collision Warning feature. Created a GUI tool to Mobile Robotics visualize objects from Radar using CAN protocol, Improved the collision warning to be robust using Bayesian filters.
  * Hands on experience training and deploying various CNN models (MobileNet, ResNet, SSD, YOLO) and LSTM based models.
  * Worked on simultaneous detection and segmentation to detect vehicles and segment lanes in a single MobileNet based network.
  * Developed a early drowsiness prediction LSTM model, optimized using TFlite Advanced Computer Vision and deployed it using Armnn on a low cost arm based harware.
  """

[[experience]]
  title = "Research Intern"
  company = "Wabco (ZF Wabco)"
  company_url = "https://www.wabco-auto.com/india/home/"
  location = "Chennai, IN"
  date_start = "2018-06-01"
  date_end = "2018-07-30"
  description = """
  Responsibilities include:
  * Worked closely with the Radar team and developed an algorithm to validate the objects from radar and camera.
  * Worked with ADAS team and improved the speed of the object detection algorithm by 1.2X - 1.5X by tweaking the model parameters.
  """
+++

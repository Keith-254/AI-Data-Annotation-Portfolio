# Lesson 04 - Image Classification

## Objective

Learn the different types of image classification used in AI data annotation.

---

# What I Learned

## 1. Image Classification

Image classification is the process of assigning one or more labels to an image based on its content.

Unlike object detection, image classification does not require drawing bounding boxes.

---

## 2. Binary Classification

Binary classification has only two possible answers.

Examples:
- Yes / No
- True / False
- Contains a Person / Does Not Contain a Person

### Example

Prompt:
Does the image contain a person?

Answer:
Yes, because a person is clearly visible in the image.

---

## 3. Multi-Class Classification

Multi-class classification requires selecting one correct label from several available options.

### Example

Image:
Truck

Options:
- Car
- Bus
- Truck
- Bicycle

Answer:
Truck, because the object belongs to the Truck class.

---

## 4. Multi-Label Classification

An image may contain several objects, so multiple labels can be correct.

### Example

Image contains:
- Person
- Dog
- Bicycle
- Tree

Selected labels:
- Person
- Dog
- Bicycle
- Tree

Ignored label:
- Car

Reason:
The image does not contain a car.

---

## 5. Fine-Grained Classification

Fine-grained classification involves choosing the most specific label that can be identified with confidence.

Example:

Options:
- Animal
- Dog
- Labrador Retriever

Correct Answer:
Dog

Reason:
The object can be confidently identified as a dog, but the breed cannot be determined. Annotators should not guess.

---

# Professional Rule

Choose the most specific label that can be identified with confidence.

Do not choose labels that are too general or guess labels that cannot be confirmed.

---

# QA Practice Completed

## Challenge 1

Decision:
Yes

Reason:
A person is clearly visible in the image.

---

## Challenge 2

Decision:
Truck

Reason:
The object belongs to the Truck class.

---

## Challenge 3

Selected Labels:
- Person
- Dog
- Bicycle
- Tree

Ignored:
- Car

Reason:
The image does not contain a car.

---

## Challenge 4

Decision:
Dog

Reason:
The object can be confidently identified as a dog, but not as a specific breed.

---

## Challenge 5

Decision:
Reject

Reason:
The annotator labeled a bicycle as a motorcycle. The object belongs to the Bicycle class.

---

# Reflection

Today I learned that image classification is different from object detection because no bounding boxes are required.

I also learned the difference between binary, multi-class, multi-label, and fine-grained classification.

The most important lesson is to choose the most specific label that can be identified with confidence while always following the annotation guidelines.

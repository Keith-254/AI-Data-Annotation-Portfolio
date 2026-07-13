# Lesson 02 - Occlusion and Truncation

## Objective

Learn how to handle partially visible objects and difficult cases in image annotation.

---

# What I Learned

## 1. Occlusion

Occlusion happens when one object blocks part of another object.

Example:
- A person standing behind a tree.
- A car behind a wall.

### Annotation Rule:

If the object can be confidently identified, annotate the visible portion only.

Do not guess hidden areas unless the project guidelines specifically require it.

---

## 2. Truncation

Truncation happens when an object is cut off by the image boundary.

Example:
- A car partly outside the camera view.
- A person cut off at the edge of an image.

### Annotation Rule:

Annotate the visible part of the object without extending the bounding box outside the image.

---

# Professional Decision Rules

Before annotating an object, ask:

1. Is this object part of the allowed class?
2. Can I confidently identify the object?
3. Am I following the annotation guidelines?

---

# Practice Exercises Completed

## Scenario 1: Person Behind a Tree

Decision:

Annotate the person because the visible features are enough to confidently identify the person.

---

## Scenario 2: Person Cut Off by Image Edge

Decision:

Annotate the person because truncation does not mean the object should be ignored.

Only annotate the visible area.

---

## Scenario 3: Crowd of People

Decision:

Annotate clearly visible people.

Ignore tiny unclear figures that cannot be confidently identified.

---

## Scenario 4: Hidden Body Behind Wall

Decision:

Reject the annotation.

The bounding box should not include guessed hidden areas. Annotators should label only the visible identifiable portion.

---

# Key Terms

| Term | Meaning |
|---|---|
| Occlusion | Object hidden by another object |
| Truncation | Object cut off by image boundary |
| Visible Portion | Area of an object that can be accurately identified |
| Confidence | Ability to identify an object reliably |
| Edge Case | A difficult annotation situation |

---

# Reflection

Today I learned that annotation is not only about drawing boxes.

A professional annotator must make careful decisions based on visibility, confidence, and project guidelines.

High-quality annotation requires consistency and accuracy.

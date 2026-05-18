<template>
    <section class="feedback-section" aria-labelledby="feedback-title">
        <div class="section-heading">
            <h2 id="feedback-title">Our coffee perfection feedback</h2>
            <p>Our customers have amazing things to say about us.</p>
        </div>

        <div class="testimonial-wrap">
            <button class="slider-btn slider-btn-prev" type="button" aria-label="Previous feedback">
                <svg class="arrow-icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                    <path d="M15 5L8 12L15 19"></path>
                </svg>
            </button>

            <figure class="testimonial-card">
                <blockquote>
                    <span aria-hidden="true">“</span>
                    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
                    industry's standard dummy text
                    ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type
                    specimen book.
                </blockquote>
                <figcaption>
                    <img src="@/assets/images/eba.png" alt="Portrait of Jonny Thomas">
                    <strong>Jonny Thomas</strong>
                    <span>Project Manager</span>
                </figcaption>
            </figure>

            <button class="slider-btn slider-btn-next" type="button" aria-label="Next feedback">
                <svg class="arrow-icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                    <path d="M9 5L16 12L9 19"></path>
                </svg>
            </button>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped></style>